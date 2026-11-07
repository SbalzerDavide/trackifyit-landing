# TrackifyIt landing

Sito pubblico di presentazione di TrackifyIt, in italiano, con identità Pulse.

## Struttura

- `index.html`: contenuti e anteprima UI con dati dimostrativi.
- `styles.css`: stile responsive e supporto al movimento ridotto.
- `assets/`: marchio e font locali. La licenza del font è in `assets/LICENSE_FONT.txt`.
- `.nojekyll`: pubblicazione statica senza elaborazione Jekyll.

Non richiede installazioni, build, backend o credenziali dell'app.

## Anteprima locale

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Aprire http://127.0.0.1:4173.

## Pubblicazione GitHub Pages

In **Settings → Pages**, scegliere **Deploy from a branch**, branch **main**, cartella **/ (root)**. Ogni push su main aggiorna il sito.

## Download iPhone

L’app è disponibile su App Store. Il link nell’header e le due CTA «Scarica su App Store» rimandano a https://apps.apple.com/it/app/trackify-it/id6779299581 (ID app `6779299581`).

## Test Android

La sezione `#android` spiega come installare l’app Android durante il test chiuso su Google Play:

1. iscriversi al gruppo Google https://groups.google.com/g/trackifyit-tester (accesso «Chiunque può partecipare»), aggiunto come lista tester del canale Alpha in Play Console;
2. accettare l’invito su https://play.google.com/apps/testing/dev.sbalzer.trackifyit;
3. installare da https://play.google.com/store/apps/details?id=dev.sbalzer.trackifyit.

Quando l’app sarà pubblica su Google Play, sostituire la sezione con un link diretto allo store e aggiornare i testi «Su Android in fase di test».

Le anteprime sono illustrative, non screenshot della versione distribuita. Quantità e obiettivi sono dati dimostrativi.
