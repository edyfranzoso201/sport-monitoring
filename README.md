# Sport Monitoring — Sito Promozionale

## Come aggiungere le immagini della gallery

Carica le immagini nella cartella `screenshots/` con questi nomi:

| File | Sezione mostrata |
|------|-----------------|
| `screenshots/home.png` | Home Riepilogo |
| `screenshots/squadra.png` | Gestione Squadra |
| `screenshots/materiale.png` | Gestione Materiale |
| `screenshots/gps.png` | GPS & Performance |
| `screenshots/calendario.png` | Calendario |
| `screenshots/valutazioni.png` | Valutazioni & Presenze |

**Dimensione consigliata:** 1280×800px, formato PNG o JPG.

Se un'immagine non è presente, viene mostrato automaticamente un placeholder.

## Come personalizzare testi e didascalie

Apri `index.html` e cerca la sezione `<!-- GALLERY -->`.
Ogni card ha:
- `gallery-title` → titolo della card
- `gallery-caption` → descrizione sotto il titolo
- `gallery-badge` → etichetta colorata sull'immagine

## Deploy

Il sito è statico — nessun server necessario.
Collega la repo a Vercel e si aggiorna automaticamente ad ogni push.
