# Rice Power - pacchetto PWA per GitHub Pages

Questa cartella contiene il gioco (`index.html`) e i file che lo rendono installabile
come app su telefoni, tablet e computer:

- `index.html` - il gioco completo (un solo file, come sempre)
- `manifest.json` - nome, icona e orientamento dell'app
- `sw.js` - service worker: fa funzionare il gioco anche offline
- `icon-*.png`, `apple-touch-icon.png`, `favicon-32.png` - icone pixel art di Giri

## Pubblicare su GitHub Pages (una volta sola, 5 minuti)

1. Crea un account gratuito su https://github.com se non lo hai.
2. In alto a destra: **+** -> **New repository**. Nome: `rice-power`. Lascialo **Public**. Clicca **Create repository**.
3. Nella pagina del repository clicca **uploading an existing file** (oppure **Add file -> Upload files**).
4. Trascina dentro TUTTI i file di questa cartella (non la cartella: i file). Clicca **Commit changes**.
5. Vai in **Settings -> Pages**. Sotto *Build and deployment*: Source = **Deploy from a branch**;
   Branch = **main**, cartella **/ (root)**. Clicca **Save**.
6. Dopo circa un minuto in alto compare l'indirizzo del gioco, del tipo
   `https://TUONOME.github.io/rice-power/`. Aprilo per verificare.

## Installare il gioco sui dispositivi

- **Android (Chrome)**: apri l'indirizzo, menu con i tre puntini -> **Installa app**
  (o **Aggiungi a schermata Home**). Si avvia a schermo intero, in orizzontale.
- **iPhone / iPad (Safari)**: apri l'indirizzo, pulsante **Condividi** -> **Aggiungi alla schermata Home**.
- **Windows / Mac / Chromebook (Chrome, Edge)**: nella barra degli indirizzi compare l'icona "Installa".
  In alternativa si gioca direttamente nel browser; il tasto **F** attiva lo schermo intero.

Dopo la prima apertura con connessione, il gioco funziona anche offline.

## Aggiornare il gioco

Quando ricevi una nuova versione di `index.html`: nel repository clicca sul file `index.html`,
poi sull'icona della matita (o **Add file -> Upload files** e sovrascrivilo), quindi **Commit changes**.
Al prossimo avvio con connessione l'app scarica da sola la versione nuova: non serve toccare `sw.js`.
