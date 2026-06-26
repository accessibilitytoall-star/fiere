# 📲 Pubblicare le Fiere su iPhone (GitHub Pages)

Questa cartella `📲 - DEPLOY/` è la versione **pronta per il web**: nomi file
semplici (senza emoji/spazi), manifest PWA e icona per la Home dell'iPhone.

## Cosa c'è
- `index.html` — indice fiere (pagina di partenza)
- `wmf-2026/index.html` — la fiera WMF 2026
- `icona-fare.png` — icona dell'app (Home iPhone)
- `manifest.webmanifest` — configurazione "Aggiungi a Home"

## Come pubblicare (come hai fatto per la Postazione Fiera)
1. Crea un repo su GitHub (es. `fiere`) e carica **il contenuto di questa
   cartella** alla radice del repo.
2. Settings → Pages → Branch `main` / cartella `/root` → Save.
3. Attendi l'URL pubblico (es. `https://<utente>.github.io/fiere/`).

## Sull'iPhone
1. Apri l'URL in **Safari**.
2. Tocca Condividi → **Aggiungi a Home**: comparirà l'icona "Fiere A2A".
3. Si apre a tutto schermo come un'app.

## Nota
- Il pulsante play, da telefono, apre Claude con il comando già pronto (non
  lancia la skill da solo: serve Claude/Cowork per quello).
- Promemoria: GitHub Pages gratuito richiede un repo **pubblico**. Se vuoi
  restare privata, pubblica solo questa cartella deploy (non l'intero workspace).
- Dopo la pubblicazione si può generare un **QR on-brand** verso l'URL.
