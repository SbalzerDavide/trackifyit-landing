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

## Attivare la prova iPhone

Le due CTA sono disabilitate perché il link App Store/TestFlight non è ancora disponibile. Quando sarà confermato, sostituire i due `button.iphone-cta` con link alla destinazione reale, eliminare i messaggi «Presto disponibile» e aggiornare «In arrivo» nell'header. Verificare la destinazione prima di pubblicare.

Le anteprime sono illustrative, non screenshot della versione distribuita. Quantità e obiettivi sono dati dimostrativi.
