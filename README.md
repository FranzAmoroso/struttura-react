# Struttura
- `src/`: Questa è la directory principale in cui si trova il codice sorgente dell'applicazione.
    - `App.jsx`: Questo file di solito contiene il componente principale dell'applicazione. È il punto di ingresso per il rendering dell'interfaccia utente.
    - `main.jsx`: Questo file è responsabile di rendere il componente principale ([App]) nell'elemento eadicw del DOM. Solitamente, contiene il codice che chiama `ReactDOM.rendere`.
    - `App.css`: Questo file di stile è spesso associato al componente principale dell'applicazione, che di solito è denominato App. In un progetto React generato con Create React App o Vite, app.css può essere importato direttamente nel componente App. Contiene le regole di stile globali o specifiche per il componente principale dell'applicazione.
    - `index.css`:Questo file di stile è spesso associato al file index.html della applicazione.Sono presenti regole di stile che si applicano globalmente a tutti gli elementi dell'app.
    - `asset/`:Alcuni progetti possono utilizzare una directory assets all'interno della directory src per organizzare file di asset, come immagini, font, stili CSS, e altro. Questi file potrebbero essere importati nei componenti React secondo le necessità.
-  `public/`: Contiene file statici e l'HTML principale dell'applicazione.
- `index.html`: il file principale che funga da modello per l'applicazione.
-  `node_modules/`: Contiene le dipendenze del progetto installare tramite npm. 
-   `package.json`: Il file di configurazione del progetto che contiene informazioni sulle dipendenze, gli script di build, i comandi di avvio e altro .
- `vite.config.js`: Questo file contiene la configurazione specifica di Vite per il progetto. Puoi personalizzare le opzioni di Vite, come le impostazioni di sviluppo e produzione. Le alias di importazione e altro ancora.
- `yarn.lock` o `package-lock.json`: File di lock delle dipendenze solitamente generato automaticamente.
### File di configurazione Aggiuntivi(opzionali)
-  `eslintrc.cjs`: Configurazione per ESlint, uno strumento di linting del codice.
-  `.gitingore`: Questo file è utilizzato per specificare quali file o cartelle devono essere ignorati da git durante il versionamento del codice. 
-  `.prettierrc`: Configurazione per Prettier, uno strumento di formattazione del codice.
- `jest.config.js`: Configurazione per Jest, il framework di testing.
- `README.md`: File di markdown.

