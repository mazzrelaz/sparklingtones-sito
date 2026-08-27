# sparklingtones.com

La pagina di presentazione di [SparklingTones](https://github.com/mazzrelaz/SparklingTones),
l'app per controllare un Positive Grid Spark 2 dal browser.

**Qui c'è solo la vetrina. L'app sta nell'altro repo**, e resta pubblicata su
`mazzrelaz.github.io/SparklingTones/` — questa pagina ci manda e basta.

## Com'è fatta

Un file HTML, niente altro: nessun build step, nessuna dipendenza, nessuna
richiesta a domini di terzi. I due caratteri (Inter e Space Grotesk, SIL OFL) e
il logo sono copiati dall'app, così le due cose sembrano la stessa.

```
index.html    tutta la pagina, stile compreso
CNAME         sparklingtones.com — è questo file che dice a GitHub Pages
              per quale dominio deve rispondere
fonts/        Inter e Space Grotesk
icons/        logo e favicon
media/        le clip video — vedi media/LEGGIMI.md
.nojekyll     dice a Pages di servire i file così come sono
```

Per vederla in locale basta aprire `index.html` con un doppio clic. I caratteri
da `file://` potrebbero non caricarsi (li blocca il browser, non è un difetto
della pagina): per vederli davvero serve un server, anche il più stupido.

## Pubblicazione

GitHub Pages, ramo `main`, cartella radice. Il dominio è impostato in
Settings → Pages e il DNS di `sparklingtones.com` (register.it) punta con
quattro record `A` agli IP di GitHub, più un `CNAME` per il `www`.

## Licenza

MIT, Massimo Togni. Nessun rapporto con Positive Grid Inc.
