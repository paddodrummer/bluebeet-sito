# BlueBeet Studio

Sito statico di BlueBeet Studio: HTML e CSS, nessuna dipendenza da installare.

- Testi e sezioni: `index.html`
- Foto: cartella `foto/`
- Pubblicazione: GitHub Pages; c'è anche la configurazione Netlify in `netlify.toml`

## Come cambiare i testi

Tutti i testi sono in `index.html`. Ogni sezione inizia con un commento, per esempio `<!-- SEZIONE CHI SIAMO -->`: cerca quel nome e cambia solo il testo tra i tag.

```html
<p class="role">Fonico, tastierista, arrangiatore.</p>
```

Cambia le parole, senza toccare `<p class="role">` e `</p>`.

| Cosa | Cerca in `index.html` |
|---|---|
| Frase principale | `<h1>` |
| Nomi degli artisti | `SEZIONE ABBIAMO LAVORATO CON` |
| Foto dei clienti | `SEZIONE CLIENTI` |
| Playlist, video, Instagram | `SEZIONE MEDIA` |
| Servizi | `SEZIONE SERVIZI` |
| Attrezzatura | `SEZIONE ATTREZZATURA` |
| Bio | `SEZIONE CHI SIAMO` |
| Telefono, email, indirizzo | `SEZIONE CONTATTI` |
| P.IVA | `P.IVA` |

Dal sito di GitHub: apri `index.html`, premi la matita, modifica e conferma con "Commit changes". Il sito online si aggiorna da solo in pochi minuti.
