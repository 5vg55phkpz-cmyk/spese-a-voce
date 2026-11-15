# Spese a voce

App web installabile (PWA) per registrare le spese a voce e vederle divise per sezione.
I dati restano sul dispositivo di ogni persona (localStorage); nessun server.

- `index.html` — l'app completa
- `sw.js` — funzionamento offline (aumentare `VERSION` a ogni rilascio)
- `manifest.webmanifest`, `icons/` — installazione sulla schermata Home
- `_headers` — intestazioni di cache per Netlify

Pubblicata su Netlify direttamente dalla cartella principale, senza comando di build.
