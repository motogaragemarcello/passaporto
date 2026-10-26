# Passaporto della moto — Moto Garage Marcello

Pagina pubblica che si apre inquadrando l'adesivo con il QR: https://passaporto.motogaragemarcello.it/#MGM-XXXX-XXXX-XXXX

Legge solo `/passaporti/{CODICE}` dal database del gestionale (regola Firebase dedicata, solo lettura di quel nodo).
Il contenuto lo scrive il gestionale (repo GESTIONALE-MOTO-GARAGE-MARCELLO, vedi il suo CLAUDE.md, sezione "Passaporto della moto").
Pubblicata con GitHub Pages dal ramo `main`; il dominio è nel file `CNAME` e nel DNS di Aruba Business (record CNAME `passaporto` → `fabioserpe.github.io`).
