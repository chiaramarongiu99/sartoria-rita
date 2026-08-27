# Atelier Rita - sito sartoria

Starter statico pronto per GitHub Pages. Include Home editoriale, catalogo filtrabile, scheda capo e viewer 360 gradi.

## 1. Personalizza
- Sostituisci email e WhatsApp in `index.html` e `prodotto.html`.
- Sostituisci testi provvisori.
- Sostituisci le immagini in `assets/images/` mantenendo gli stessi nomi oppure aggiorna i percorsi HTML.
- Per il 360 inserisci 24 fotografie in `assets/360/abito-lino/` chiamate `frame-01.jpg` ... `frame-24.jpg`.

Nota: i 24 frame inclusi sono duplicati segnaposto, quindi il viewer funziona ma non mostra ancora una vera rotazione.

## 2. Prova in locale
Non aprire solo il file con doppio clic. Avvia un server locale:

```bash
python3 -m http.server 8080
```

Poi visita `http://localhost:8080`.

## 3. Pubblica su GitHub Pages
1. Crea un repository pubblico, per esempio `merri-rita`.
2. Carica tutti i file di questa cartella nella root del repository.
3. In GitHub apri `Settings > Pages`.
4. In `Build and deployment`, scegli `Deploy from a branch`.
5. Seleziona branch `main` e cartella `/(root)`, poi salva.

Il sito sarà disponibile all'indirizzo mostrato da GitHub Pages.

## 4. Comandi Git
```bash
git init
git add .
git commit -m "Initial Atelier Rita website"
git branch -M main
git remote add origin URL_DEL_REPOSITORY
git push -u origin main
```

## Copyright
Le immagini provvisorie presenti nel pacchetto sono state generate per questo prototipo. Sostituiscile con fotografie originali di Atelier Rita prima della pubblicazione definitiva.
