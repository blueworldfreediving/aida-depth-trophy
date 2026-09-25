# Blue World Freediving — AIDA Depth Trophy · sito evento

Sito statico: un solo file `index.html` + cartella `img/`.
Tutti i contenuti che cambiano (news, atleti, programma, partner, foto, rassegna stampa)
sono nel blocco `const DATA = { ... }` in cima a `index.html`.

## Aggiornare il sito
1. Su GitHub apri `index.html` e clicca la matita (Modifica).
2. Cambia solo il blocco DATA (aggiungi una riga a `news`, `press`, `gallery`, `partners`…).
3. "Commit changes" → dopo 1–2 minuti il sito è aggiornato.

Nuove foto: caricale nella cartella `img/` (Add file → Upload files) e richiamale come `img/nome.jpg`.

## Regole già nel codice
- partner privati: compaiono solo con `status: "public"`
- news con `published: false` restano nascoste
- sezioni vuote mostrano un testo di attesa, mai un buco

## Contatore visite (solo admin)
Attivare GoatCounter (gratuito, senza cookie): creare un account su goatcounter.com,
poi incollare lo script fornito subito prima di `</body>` in `index.html`.
Le statistiche si vedono solo nella dashboard GoatCounter.
