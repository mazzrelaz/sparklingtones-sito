# I video e le immagini della pagina

Qui dentro vanno le clip. La pagina è già pronta per riceverle: in `index.html`
ci sono due blocchi commentati, uno dopo l'apertura e uno dopo la guida, con
scritto sopra cosa fare.

## Come si aggiunge una clip

1. Metti il file qui, con uno di questi nomi:
   - `apertura.mp4` — la clip grande, subito sotto il titolo
   - `libreria.mp4` — la libreria che si popola leggendo dall'ampli
   - `live.mp4` — i pulsantoni della vista live premuti uno dopo l'altro
   - `editor.mp4` — una manopola girata, con l'ampli che risponde
2. Apri `index.html`, trova il blocco commentato che la riguarda e togli
   il commento (le righe `<!-- ... -->` che lo racchiudono).
3. Se hai anche un fermo immagine, chiamalo con lo stesso nome ma `.jpg`
   (`apertura.jpg`): serve a far vedere qualcosa prima che il video parta.

## Come registrarle

- **Orizzontale**, sempre. Una clip verticale su una pagina larga sta male.
- **20-40 secondi.** Sono clip che girano in loop accanto al testo, non un
  tutorial: devono far capire la forma della cosa, non spiegarla.
- **Senza audio**, tranne quella dell'editor: lì il suono è il punto, e infatti
  quella è l'unica con i controlli e senza autoplay.
- Sul telefono va bene il registratore schermo di Android; su PC, Win+G
  (Xbox Game Bar) oppure OBS.
- La clip dell'editor **riprendila col telefono**, inquadrando ampli e schermo
  insieme: deve vedersi che il suono cambia mentre la manopola si muove. È
  l'unica cosa che una registrazione dello schermo non può mostrare.

## Peso

Una clip 1080p da 30 secondi sta in 3-8 MB, e GitHub Pages la serve senza
problemi. Se una supera i 20 MB conviene ricomprimerla: nessuno aspetta.
