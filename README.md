# professorfigura.it — repo pubblica del sito

Sito statico (HTML/CSS/JS puro, nessuna build necessaria).

## Struttura
- `index.html` — homepage
- `chi-sono/index.html` — pagina Chi sono
- `argomenti/<slug>/index.html` — una cartella per ogni lezione (36 argomenti)
- `prof-figura-v2.jpg` — foto del prof. Figura, usata in homepage e Chi sono

## Pubblicazione con GitHub Pages
1. Crea/apri il repository su GitHub (es. `professorfigura-sito`)
2. Impostazioni → Pages → Deploy from branch → branch `main`, cartella `/ (root)`
3. Se usi un dominio personalizzato (professorfigura.it), aggiungi un file `CNAME` nella root con dentro `professorfigura.it`, e configura il DNS del dominio (record A verso gli IP di GitHub Pages, o CNAME verso `<utente>.github.io`)
