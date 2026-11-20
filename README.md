# ASCII Flower Bouquet 💐

Mazzo di fiori ASCII 3D animato, visibile direttamente dal browser (anche da telefono).

**Demo:** https://codealchemist-ita.github.io/bouquet/

## Origine

Port JavaScript di [`bouquet3d.py`](https://github.com/alishsharma17/Ascii-Flower-Bouquet-)
di **Alish Sharma** (licenza MIT), nato come animazione per terminale.

La logica è la stessa (scena 3D, proiezione prospettica, shading, z-buffer); cambiano solo:

- **Output su `<canvas>`** invece di codici ANSI, nitido sugli schermi ad alta densità.
- **Griglia adattiva**: ~108 colonne su telefono, fino a 180 su desktop.
- **Riempimento colore** dietro ogni carattere e campionamento più denso, così la sagoma resta leggibile su schermi piccoli.

## Uso

È un singolo file `index.html` senza dipendenze: aprilo nel browser o pubblicalo su qualsiasi hosting statico.

## Licenza

MIT — vedi [LICENSE](LICENSE).
