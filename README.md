# 🍣 Rice Power — La leggenda del Riso Supremo

**[▶ Gioca ora](https://lukslx.github.io/rice-power/)** — direttamente nel browser, su PC, tablet e telefono. Gioco completo, versione 1.0.

Un action-adventure pixel art con visuale dall'alto, nello spirito dei classici 8-bit, con un protagonista insolito: un nigiri al salmone che non ha nessuna intenzione di farsi mangiare.

> Ristorante Karaguashi. Ore 20:47. Tavolo 12 aspetta il suo nigiri.
> Ma questo nigiri si chiama Giri, e stasera scappa.

## La storia

Giri salta giù dal piatto e fugge dal ristorante. In città incontra Onigiri, un vecchio e misterioso onigiri che conosce un'antica leggenda: ogni sushi contiene un po' di **Rice Power**, ma esistono rarissimi **Chicchi del Riso Supremo** capaci di moltiplicarla. Chi li riunisce risveglia il **Cuore del Sushi Supremo**… e l'ultimo frammento è nelle mani dello Chef Karaguashi.

Il viaggio attraversa cinque mondi:

1. **Prologo — La fuga** dal ristorante e la città, fino al parco dove aspetta Onigiri.
2. **La Risaia di Montagna** — cervi che caricano, branchi di lupi, orsi affamati e il Grande Orso della Risaia.
3. **L'Isola del Vulcano** — calamari di fuoco, serpenti velenosi, polli con la mitragliatrice e Tako Inferno nel cratere.
4. **La Città Invasa** — alieni ossessionati dal sushi, barriere laser, il Razzo Rimbalzo e l'Imperatore Gnam-Zor.
5. **Ritorno al Karaguashi** — sala, cucina, magazzino, cella frigorifera, i sushi da liberare e lo Chef in tre fasi. Poi il finale.

Più si va avanti, più il mondo diventa assurdo. Nessuno lo spiega: è semplicemente Rice Power.

## Come si gioca

Apri il link qui sopra e premi **Gioca**. Non serve installare nulla.

Per averlo sulla schermata Home come un'app (a schermo intero e anche offline):

- **Android** (Chrome): menu ⋮ → *Installa app*
- **iPhone / iPad** (Safari): *Condividi* → *Aggiungi alla schermata Home*
- **Windows / Mac / Chromebook**: icona *Installa* nella barra degli indirizzi, oppure tasto **F** per lo schermo intero

### Controlli

| Azione | PC | Tablet / telefono |
|---|---|---|
| Muoversi | Frecce o WASD | Levetta virtuale (metà sinistra dello schermo) |
| Sparare salsa di soia | SPAZIO o click (si può tenere premuto, con il mouse si mira) | Pulsante **ATTACCO** |
| Schivata | SHIFT | Pulsante **SCHIVATA** |
| Abilità (Wasabi o Razzo Rimbalzo) | E | Pulsante **ABILITÀ** |
| Cambiare abilità | Q (oppure 1 / 2) | Pulsante **CAMBIA** |
| Pausa | ESC | Pulsante **II** |
| Audio on/off | M | — |
| Schermo intero | F | pulsante in alto (dove supportato) |

Suggerimenti: la pistola non è in mano a Giri all'inizio, va trovata. La schivata rende invulnerabili per un istante: è il modo giusto per passare attraverso una carica. Il Wasabi confonde i nemici (anche i boss, ma per poco). Il Razzo Rimbalzo rispedisce i colpi nemici a chi li ha sparati, con danno doppio. Ogni boss ha un momento di debolezza: quando sbatte, quando è stordito, quando riemerge.

## Tecnica

- Un solo file HTML (`index.html`), nessuna libreria, nessuna immagine, nessun file audio.
- Tutta la grafica è disegnata via Canvas 2D a 384×216 pixel e scalata con pixel netti; il font è una bitmap 5×7 con gli accenti italiani.
- Musica e effetti sonori sono sintetizzati con la Web Audio API.
- Le mappe sono griglie di caratteri generate da codice e pre-renderizzate; collisioni rettangolari asse per asse.
- `manifest.json`, `sw.js` e le icone rendono il gioco installabile e giocabile offline.

## Fare una copia

Fai il fork del repository oppure scarica `index.html`: si apre con un doppio clic in qualsiasi browser moderno. Per pubblicare la tua versione basta attivare GitHub Pages sul branch `main`.

## Crediti

Idea, storia e game design: **lukslx**. Codice e pixel disegnati via codice realizzati con l'aiuto di **Claude** (Anthropic).

Nessun sushi è stato mangiato nella realizzazione di questo gioco.
