# Lightning Checkout WordPress Plugin

Lightning Checkout is een WordPress-plugin die de betalingsverwerking mogelijk maakt via [Lightning Checkout](https://lightningcheckout.eu/nl/).

## Functies
- Gemakkelijk te integreren met elke WordPress-website via een shortcode
- Ondersteunt aanpassingen van betalingsbedrag, beschrijving en terugkeer-URL via shortcode-attributen
- Maakt gebruik van de Lightning Checkout API voor betalingsverwerking

## Installatie
1. Download de zip-bestand van deze GitHub-repository
2. Ga naar de WordPress-admin > Plugins > Nieuwe toevoegen
3. Klik op 'Plugin uploaden' en selecteer het gedownloade zip-bestand
4. Na het uploaden, activeer de plugin

## Configuratie
Ga naar Instellingen > Lightning Checkout in je WordPress-admin om de vereiste instellingen in te vullen, zoals API-sleutel, URL, en standaardinstellingen.

## Gebruik
Voeg de volgende shortcode toe aan een bericht, pagina of widget om de Lightning Checkout-betalingsinterface weer te geven:

```
[lightning_payment]
```

Je kan ook de volgende attributen gebruiken om specifieke betalingsdetails in te stellen:

- `amount`: Het bedrag voor de betaling
- `description`: De beschrijving van de betaling
- `returnurl`: De URL waar gebruikers naartoe worden omgeleid na de betaling

Bijvoorbeeld:

```
[lightning_payment amount="0.50" description="Aanmelding" returnurl="https://www.voorbeeld.nl"]
```

## Ondersteuning
Voor ondersteuning, open een nieuw issue op deze GitHub-repository.

## Licentie
Deze plugin is vrijgegeven onder de GNU General Public License v3.0.