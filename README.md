# 🍣 Rice Power — La leggenda del Riso Supremo

**[▶ Gioca ora](https://lukslx.github.io/rice-power/)** — direttamente nel browser, su PC, tablet e telefono.

Un piccolo action-adventure pixel art con visuale dall'alto, nello spirito dei classici 8-bit, con un protagonista insolito: un nigiri al salmone che non ha nessuna intenzione di farsi mangiare.

> Ristorante Karaguashi. Ore 20:47. Tavolo 12 aspetta il suo nigiri.
> Ma questo nigiri si chiama Giri, e stasera scappa.

## La storia

Giri salta giù dal piatto e fugge dal ristorante. In città incontra Onigiri, un vecchio e misterioso onigiri che conosce un'antica leggenda: ogni sushi contiene un po' di **Rice Power**, ma esistono rarissimi **Chicchi del Riso Supremo** capaci di moltiplicarla. Chi li riunisce risveglia il **Cuore del Sushi Supremo**… e l'ultimo frammento è nelle mani dello Chef Karaguashi.

Inizia così un viaggio tra risaie di montagna, isole vulcaniche e città invase dagli alieni, per poi tornare al ristorante e liberare gli altri sushi. Più si va avanti, più il mondo diventa assurdo. Nessuno lo spiega: è semplicemente Rice Power.

## Come si gioca

Apri il link qui sopra e premi **Gioca**. Non serve installare nulla.

Se vuoi il gioco sulla schermata Home come un'app (a schermo intero e anche offline):

- **Android** (Chrome): menu ⋮ → *Installa app*
- **iPhone / iPad** (Safari): *Condividi* → *Aggiungi alla schermata Home*
- **Windows / Mac / Chromebook**: icona *Installa* nella barra degli indirizzi, oppure tasto **F** per lo schermo intero

### Controlli

| Azione | PC | Tablet / telefono |
|---|---|---|
| Muoversi | Frecce o WASD | Levetta virtuale (metà sinistra dello schermo) |
| Sparare salsa di soia | SPAZIO o click (si può tenere premuto, con il mouse si mira) | Pulsante **ATTACCO** |
| Schivata | SHIFT | Pulsante **SCHIVATA** |
| Sputare Wasabi | E | Pulsante **ABILITÀ** |
| Pausa | ESC | Pulsante **II** |
| Audio on/off | M | — |
| Schermo intero | F | pulsante in alto (dove supportato) |

Suggerimenti: la pistola non è in mano a Giri all'inizio, va trovata. Senza salsa di soia Giri si difende a testate di riso. La schivata rende invulnerabili per un istante: è il modo giusto per passare attraverso una carica. E tieni d'occhio i muri con le crepe.

## Cosa contiene questa versione (v0.1 — Prologo)

- La fuga dal ristorante Karaguashi, tra camerieri che caricano e clienti che lanciano bacchette
- La città, con cittadini affamati, gatti randagi, piccioni in picchiata, un vicolo segreto e il parco dove aspetta Onigiri
- Pistola alla salsa di soia con munizioni, Wasabi che confonde i nemici, Tonno XL e Zenzero per curarsi
- Schivata con frame di invulnerabilità, cuori, Rice Power, dialoghi, game over e un finale di prologo

## Prossimamente

- **Mondo 1 — Campagna e Risaia di Montagna**: cervi, lupi, orsi e il Grande Orso della Risaia. Primo Chicco Supremo.
- **Mondo 2 — Isola del Vulcano**: calamari di fuoco, serpenti velenosi, il Pollo Mitragliere e Tako Inferno.
- **Mondo 3 — La Città Invasa**: alieni, droni, laser, il Razzo Rimbalzo e l'Imperatore Gnam-Zor.
- **Finale — Ritorno al Karaguashi**: la liberazione degli altri sushi e lo scontro in tre fasi con lo Chef.

## Com'è fatto

Tutto il gioco è in un unico file, `index.html`: HTML, CSS e JavaScript senza librerie. La grafica è disegnata interamente via codice su Canvas (pixel art a 384×216 scalata), il font è un bitmap 5×7 fatto a mano, i suoni e la musica chiptune sono sintetizzati con la Web Audio API. Gli altri file del repository (`manifest.json`, `sw.js`, le icone) servono solo a renderlo installabile e giocabile offline.

Per avere una copia del gioco basta scaricare `index.html` e aprirlo con doppio click.

## Pubblicare la propria copia

Fai un fork di questo repository, poi in *Settings → Pages* scegli *Deploy from a branch*, branch `main`, cartella `/ (root)`. In un minuto il gioco è online al tuo indirizzo GitHub Pages.

## Crediti

Ideazione, storia e game design: **lukslx**.
Codice e grafica procedurale sviluppati con l'aiuto di Claude (Anthropic).

Rice Power è un progetto amatoriale senza fini di lucro. Tutti i personaggi sono originali.
