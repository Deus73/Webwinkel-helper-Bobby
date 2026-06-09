# Installatie En Veiligheid

Deze repository deelt geen installatiepakket. De onderstaande informatie beschrijft alleen hoe Bobby bedoeld is om veilig te worden gebruikt.

## Veilige Start

Bobby start standaard in Ghostmode. Daardoor kunnen admins de frontend controleren voordat bezoekers de helper zien.

Aanbevolen volgorde:

1. Installeer Bobby in WordPress.
2. Controleer de instellingenpagina.
3. Stel naam, avatar, knoptekst, knoplocatie, taal en reactiestijl in.
4. Controleer Bobby-tijden en Chatbot-overname.
5. Test als ingelogde admin op de frontend.
6. Zet Bobby pas daarna Live.

## Testvragen

Gebruik onder andere:

- Waar is mijn bestelling?
- Ik wil retourneren.
- Vind zwarte schoenen maat 42.
- Leg uit waarom dit product beter is.

De laatste vraag hoort niet tot productadvies te leiden. Bobby moet weigeren om productuitleg of vergelijking te verzinnen en kan in plaats daarvan zoeken of doorverwijzen.

## Beveiliging

- API-sleutels horen alleen op de server, nooit in browsercode.
- Ordergegevens worden alleen getoond na veilige klantmatch.
- Niet-ingelogde bezoekers moeten ordernummer plus postcode of e-mailadres geven.
- Wijzigingen aan orders, adressen, producten, prijzen, aantallen, betalingen of accounts blijven bij de admin of het bestaande shopsysteem.
- Refunds, betalingen en gevoelige accountwijzigingen vereisen menselijke bevestiging.
- Logboeken kunnen privacyvriendelijk worden gemaskeerd.

## Technische Eisen

De lokale pluginmetadata noemt:

- WordPress 6.0 of hoger.
- PHP 7.4 of hoger.
- WooCommerce voor order- en productfuncties.
