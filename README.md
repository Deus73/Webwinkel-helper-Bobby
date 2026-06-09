# Webwinkel Helper Bobby

Publieke informatiepagina voor Webwinkel Helper Bobby: een WordPress/WooCommerce klanthelper voor webwinkels. Deze repository bevat uitleg, kosteninformatie en screenshots. De plugin zelf wordt hier niet gedeeld.

Website en contact: https://www.digitaldopeadvisors.com

## Wat Bobby Doet

Bobby helpt webwinkelbezoekers met veelvoorkomende supportvragen, zonder dat hij gevoelige winkelgegevens kan aanpassen. De helper is bedoeld als duidelijke supportlaag naast WooCommerce.

- Chatknop op de webwinkel met eigen naam, avatar, knoptekst en positie.
- Veilig starten via `Uit`, `Ghostmode` en `Live`.
- Ghostmode toont Bobby alleen aan ingelogde administrators.
- Nieuwe installaties en updates starten standaard veilig in Ghostmode.
- Bobby-tijden: standaard is Bobby aanwezig van 11:00 tot 18:00; daarbuiten kan de Chatbot overnemen.
- Scenario-antwoorden voor bestelling, track & trace, retour, betaling, login, beschadigde of verkeerde levering, contact, openingstijden, privacy en klachten.
- WooCommerce-orderhulp voor ingelogde klanten.
- Gastcontrole met ordernummer plus postcode of e-mailadres.
- Producten zoeken en filteren, zonder productadvies of verzonnen productuitleg.
- Logboek voor bezoekers en compleet backend-logboek voor admins.
- Print/PDF-knop voor gesprekken.
- Feedbackknoppen bij antwoorden.
- Reactiestijlen zoals zeer beleefd, grappig, direct, snauwend of neutraal.
- Privacy-optie om e-mailadressen en lange nummers in admin-logboeken te maskeren.
- Performancebegrenzing, waaronder beperkte chatgeschiedenis, maximaal vijf productresultaten en maximaal duizend logregels.
- REST-backend is ingebouwd; een externe backend is optioneel.

## Veiligheidsgrenzen

Bobby is ontworpen als read-only klanthelper. Hij mag informatie geven, verduidelijkingsvragen stellen en bezoekers doorverwijzen naar support, maar hij mag niet zelfstandig orders, adressen, producten, prijzen, aantallen, betalingen, refunds of accountgegevens wijzigen.

API-sleutels horen nooit in browsercode. Gebruik daarvoor altijd een serverendpoint.

## Pakketten En Kosten

De lokaal voorbereide Bobby-producten gebruiken deze prijzen:

| Pakket | Prijs | Bedoeld voor |
| --- | ---: | --- |
| Bobby Standard | EUR 149 | Webwinkels die veilig willen starten met Ghostmode, basisantwoorden, chatknop, print/PDF en adminlogboek. |
| Bobby Premium | EUR 349 | Shops die Bobby actief willen inzetten met WooCommerce-orderhulp, gastcontrole, meer scenario's, uitgebreider logboek en Bobby-tijden. |
| Bobby Lifetime | EUR 799 | Ondernemers die eenmalig willen instappen, toekomstige upgrades binnen dezelfde hoofdversie willen en ruimte voor groei of maatwerk nodig hebben. |

Betaalproviderkosten, hosting, WooCommerce-beheer, maatwerk, supportafspraken en eventuele AI- of serverkosten vallen buiten deze productprijzen.

Meer details staan in [docs/kosten.md](docs/kosten.md).

## Screenshots

Live demo van de Bobby-verkooppagina:

![Bobby live demo verkooppagina](screenshots/demo-verkooppagina-home.jpg)

Publieke uitleg en kostenoverzicht:

![Bobby overzicht](screenshots/bobby-overzicht.jpg)

![Bobby kosten en veiligheid](screenshots/bobby-kosten-veiligheid.jpg)

## Wat Niet In Deze Repository Staat

Deze repository bevat geen pluginbroncode, geen zipbestanden, geen updater en geen private installatiepakketten. Dit is bewust gedaan zodat de werking publiek kan worden uitgelegd zonder de plugin zelf te verspreiden.

## Documentatie

- [Mogelijkheden](docs/mogelijkheden.md)
- [Kosten](docs/kosten.md)
- [Installatie en veiligheid](docs/installatie-en-veiligheid.md)
