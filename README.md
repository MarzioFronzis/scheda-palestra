# Scheda Ripartenza

Web app statica mobile-first per la scheda di allenamento "Ripartenza — Settembre 2026".

## Funzioni

- 3 giornate di allenamento: A, B e C
- Navigazione su 8 settimane
- Range di carico consigliati
- Registrazione dei carichi tramite `localStorage`
- Spunta degli esercizi completati
- Timer di recupero
- Vibrazione a fine recupero, quando supportata dal dispositivo
- Reset delle spunte della settimana corrente
- Nessun backend e nessun account necessario

## Avvio locale

Apri semplicemente `index.html` nel browser.

## Pubblicazione con GitHub Pages

Il repository contiene anche un workflow GitHub Actions in `.github/workflows/pages.yml`.

Dopo aver caricato il progetto su GitHub:

1. apri **Settings → Pages**
2. in **Build and deployment**, seleziona **GitHub Actions**
3. il workflow pubblicherà automaticamente il sito ad ogni push su `main`

## Dati

I pesi e le spunte vengono salvati nel `localStorage` del browser. Restano quindi sul dispositivo/browser utilizzato e non vengono sincronizzati online.
