# Portfolio — Fabrizio Napoli

Sito statico a pagina singola, pronto per GitHub Pages. Nessuna build necessaria: è un unico file `index.html` (font caricati da Google Fonts via CDN).

## Pubblicare su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `fabrizio-napoli-portfolio`).
2. Carica `index.html` nella root del repository (via web: "Add file → Upload files", oppure via git: `git add index.html && git commit -m "portfolio" && git push`).
3. Vai su **Settings → Pages** del repository.
4. In "Build and deployment", seleziona **Deploy from a branch**, branch `main`, cartella `/root`.
5. Salva: dopo circa un minuto il sito sarà live su `https://<tuo-utente>.github.io/<nome-repo>/`.

Se vuoi che il sito sia raggiungibile su `https://<tuo-utente>.github.io/` direttamente (senza sotto-percorso), chiama il repository `<tuo-utente>.github.io`.

## Modificare i contenuti

Tutto il testo è dentro `index.html` in chiaro (nessun template esterno): cerca il progetto o la sezione che vuoi cambiare e modifica direttamente il testo tra i tag HTML.
