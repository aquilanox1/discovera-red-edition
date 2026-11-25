# Discovera Red Edition — PWA

Versione web installabile (PWA), pronta per GitHub Pages.

## Pubblicazione su GitHub Pages
1. Crea un repository GitHub chiamato `discovera-red-edition`.
2. Carica **tutti** i file e le cartelle di questo progetto nella root del repository.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **GitHub Actions**.
5. Vai in **Actions** e attendi il completamento di `Deploy PWA to GitHub Pages`.
6. Il sito sarà disponibile a `https://TUO-USERNAME.github.io/discovera-red-edition/`.

## Funzioni
- Interfaccia responsive dark / red, stile glass.
- Installabile su Android e iPhone (Aggiungi a schermata Home).
- Cache offline della struttura dell'app.
- Collegamenti a catalogo, categorie, blog e sito ufficiale.
- Prenotazioni e pagamenti restano su Discovera.it.

## Limiti attuali
Questa PWA non dispone di un'API ufficiale Discovera. Perciò i link alle categorie e al catalogo aprono le pagine ufficiali; non vengono simulati disponibilità, prezzi live o notifiche push. Per catalogo nativo completo e push reali serve un feed/API autorizzato e un backend.
