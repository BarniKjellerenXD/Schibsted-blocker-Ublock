# Schibsted Blocker

uBlock Origin-filter som blokkerer Schibsteds «pay-to-reject» CMP-popup.
Dekker alle Schibsteds norske nettsteder.

## Dekkede nettsteder

| Domene | Type |
|--------|------|
| vg.no | Nyheter |
| aftenposten.no | Nyheter |
| bt.no (Bergens Tidende) | Nyheter |
| aftenbladet.no (Stavanger Aftenblad) | Nyheter |
| e24.no | Næringsliv |
| tek.no / tu.no (Teknisk Ukeblad) | Teknologi |
| digi.no | Teknologi |
| shifter.no | Startup/teknologi |
| minmote.no | Mote |
| godt.no | Mat/middag |
| vektklubb.no | Helse/vekt |
| finn.no | Markedsplass |
| prisjakt.no | Prisammenligning |

## Hvorfor

Schibsted tvinger deg til å **betale for å avvise personlig tilpasset annonsering**
på VG.no og deres andre sider. Dette er en omgåelse av GDPR og norsk
personvernlovgivning. Inntil myndighetene får stanset det, fikser uBlock problemet.

## Manuell installasjon

1. Åpne uBlock Origin Dashboard (klikk ikonet → tannhjulet)
2. Gå til **My filters**
3. Lim inn innholdet fra [`schibsted-blocker.txt`](schibsted-blocker.txt)
4. Klikk **Apply changes**
5. Oppdater siden du vil besøke

## Automatisk abonnement

1. Åpne uBlock Origin Dashboard
2. Gå til **Filter lists** → scroll ned til **Import**
3. Lim inn: `https://raw.githubusercontent.com/BarniKjellerenXD/Schibsted-blocker-Ublock/main/schibsted-blocker.txt`
4. Klikk **Apply changes**

## Bidra

Ser du et Schibsted-nettsted som mangler? Åpne en issue eller send en PR!

## Lisens

MIT — gjør hva du vil med den.
