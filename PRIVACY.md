# MC Navigator — Privacy Policy

_Last updated: 15 October 2026_

🇮🇹 [Versione italiana più sotto](#informativa-sulla-privacy)

MC Navigator is a Chrome extension that helps users of Salesforce Marketing Cloud Engagement explore the metadata of their business unit (Data Extensions, automations, queries, scripts, journeys, file imports) and its data lineage.

## What data the extension handles

- **Marketing Cloud metadata**: names, keys and folders of Data Extensions, automations, queries, scripts, journeys, imports and file activities; SQL and script code; Content Builder emails, content blocks and CloudPages with their HTML / AMPscript code (images and documents are not stored); Data Extension fields.
- **Data Extension records**: only when the user opens them. The record viewer reads the rows of one Data Extension from Marketing Cloud and shows them without storing them. The SQL editor stores in the browser the user's worksheets and, for each worksheet, the history of the last 15 runs with their results (up to 5,000 rows per run), so that a result can be opened again; the user can delete a run or a worksheet's history at any time. These records may contain personal data of the user's contacts (for example e-mail addresses): the extension handles them only on behalf of the user and never sends them outside the user's browser and Marketing Cloud account.
- **Connection settings**: in "Installed Package" mode, the Client ID, Client Secret, subdomain and MID entered by the user. In "Marketing Cloud session" mode no credentials are entered or stored: the extension uses the session already open in the user's browser.
- **Preferences**: interface language, last selected tab and connection, editor options.

## Where the data goes

- All data is stored **only in the user's browser** (`chrome.storage.local` and `localStorage`).
- Data is exchanged **only with the user's own Salesforce Marketing Cloud instance** (`*.exacttarget.com` and `*.marketingcloudapis.com`), using GET requests and, in "Installed Package" mode, the OAuth token request. Only if the user turns on editing in Settings, the extension also sends to the user's Marketing Cloud instance the text of a query, script or Content Builder asset the user saves, the Data Extension rows the user edits, adds, imports or deletes, and the queries the user runs from the SQL editor.
- There is **no MC Navigator server**. The extension does not send data to the developer or to third parties, and it contains no analytics, advertising or tracking.
- Without that option the extension changes nothing in Marketing Cloud. With it, it changes only the queries, scripts and Content Builder assets the user edits and saves explicitly, and the Data Extension rows the user edits, adds, imports from a CSV file or marks for deletion in the record viewer, after a summary of the changes. To run a query from the SQL editor it creates a temporary query and Data Extension and deletes them right after; "Save to DE" creates the Data Extension and, if the user asks for it, the Query Activity. Apart from the rows the user deletes, it never deletes anything it did not create. CSV files are read in the browser and their rows are sent only to the user's Marketing Cloud account.
- Excel exports are generated locally and saved only where the user chooses.

## Data retention and deletion

Data remains in the browser until the user deletes it. From Settings the user can clear the local index or remove a connection, together with its credentials and index. Uninstalling the extension deletes all of its data.

## Security

In "Installed Package" mode the Client Secret is stored unencrypted in the browser's extension storage. We recommend using a dedicated Installed Package with read-only permissions, or the "Marketing Cloud session" mode, which stores no credentials.

## Changes and contact

Changes to this policy will be published on this page. For questions write to: **fusi.danilo@gmail.com**.

MC Navigator is an independent tool and is not affiliated with, endorsed or sponsored by Salesforce, Inc. Salesforce and Marketing Cloud are trademarks of Salesforce, Inc.

---

# Informativa sulla privacy

_Ultimo aggiornamento: 15 ottobre 2026_

MC Navigator è un'estensione di Chrome che aiuta chi usa Salesforce Marketing Cloud Engagement a esplorare i metadati della propria business unit (Data Extension, automation, query, script, journey, file import) e la lineage dei dati.

## Quali dati tratta l'estensione

- **Metadati di Marketing Cloud**: nomi, key e cartelle di Data Extension, automation, query, script, journey, import e attività sui file; codice SQL e degli script; email, content block e CloudPages di Content Builder con il loro codice HTML / AMPscript (immagini e documenti non vengono salvati); campi delle Data Extension.
- **Record delle Data Extension**: solo quando l'utente li apre. Il record viewer legge da Marketing Cloud le righe di una Data Extension e le mostra senza salvarle. L'editor SQL salva nel browser i fogli dell'utente e, per ogni foglio, la cronologia delle ultime 15 esecuzioni con i risultati (fino a 5.000 righe per esecuzione), per poter riaprire un risultato; l'utente può eliminare un'esecuzione o la cronologia di un foglio in qualsiasi momento. Questi record possono contenere dati personali dei contatti dell'utente (per esempio indirizzi e-mail): l'estensione li tratta solo per conto dell'utente e non li invia mai fuori dal browser e dall'account Marketing Cloud dell'utente.
- **Impostazioni di connessione**: in modalità "Installed Package", Client ID, Client Secret, subdomain e MID inseriti dall'utente. In modalità "sessione di Marketing Cloud" non viene inserita né salvata alcuna credenziale: l'estensione usa la sessione già aperta nel browser.
- **Preferenze**: lingua dell'interfaccia, ultima scheda e connessione selezionate, opzioni dell'editor.

## Dove vanno i dati

- Tutti i dati sono salvati **solo nel browser dell'utente** (`chrome.storage.local` e `localStorage`).
- I dati vengono scambiati **solo con l'istanza Salesforce Marketing Cloud dell'utente** (`*.exacttarget.com` e `*.marketingcloudapis.com`), con richieste GET e, in modalità "Installed Package", con la richiesta del token OAuth. Solo se l'utente attiva la modifica nelle Impostazioni, l'estensione invia anche all'istanza Marketing Cloud dell'utente il testo delle query, degli script e dei contenuti di Content Builder che salva, le righe delle Data Extension che modifica, aggiunge, importa o elimina e le query che esegue dall'editor SQL.
- **Non esiste un server di MC Navigator**. L'estensione non invia dati allo sviluppatore né a terzi e non contiene analytics, pubblicità o tracciamento.
- Senza quell'opzione l'estensione non modifica nulla in Marketing Cloud. Con l'opzione attiva modifica solo le query, gli script e i contenuti di Content Builder che l'utente modifica e salva esplicitamente, e le righe delle Data Extension che l'utente modifica, aggiunge, importa da un file CSV o segna da eliminare nel record viewer, dopo un riepilogo delle modifiche. Per eseguire una query dall'editor SQL crea una query e una Data Extension temporanee e le elimina subito dopo; "Salva in DE" crea la Data Extension e, se l'utente lo chiede, la Query Activity. A parte le righe che l'utente elimina, non elimina mai nulla che non abbia creato. I file CSV vengono letti nel browser e le loro righe sono inviate solo all'account Marketing Cloud dell'utente.
- Gli export Excel vengono generati in locale e salvati solo dove sceglie l'utente.

## Conservazione e cancellazione

I dati restano nel browser finché l'utente non li elimina. Dalle Impostazioni si può svuotare l'indice locale o rimuovere una connessione, insieme alle sue credenziali e al suo indice. Disinstallando l'estensione vengono eliminati tutti i suoi dati.

## Sicurezza

In modalità "Installed Package" il Client Secret è salvato non cifrato nello storage dell'estensione. Si consiglia di usare un Installed Package dedicato con permessi di sola lettura, oppure la modalità "sessione di Marketing Cloud", che non salva credenziali.

## Modifiche e contatti

Le modifiche a questa informativa saranno pubblicate in questa pagina. Per domande scrivi a: **fusi.danilo@gmail.com**.

MC Navigator è uno strumento indipendente, non affiliato, approvato o sponsorizzato da Salesforce, Inc. Salesforce e Marketing Cloud sono marchi di Salesforce, Inc.
