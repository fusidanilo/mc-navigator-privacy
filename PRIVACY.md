# MC Navigator — Privacy Policy

_Last updated: 10 October 2026_

🇮🇹 [Versione italiana più sotto](#informativa-sulla-privacy)

MC Navigator is a Chrome extension that helps users of Salesforce Marketing Cloud Engagement explore the metadata of their business unit (Data Extensions, automations, queries, scripts, journeys, file imports) and its data lineage.

## What data the extension handles

- **Marketing Cloud metadata**: names, keys and folders of Data Extensions, automations, queries, scripts, journeys, imports and file activities; SQL and script code; Data Extension fields. When the user explicitly asks for it, a preview of up to 50 rows of one Data Extension is shown and not stored.
- **Connection settings**: in "Installed Package" mode, the Client ID, Client Secret, subdomain and MID entered by the user. In "Marketing Cloud session" mode no credentials are entered or stored: the extension uses the session already open in the user's browser.
- **Preferences**: interface language, last selected tab and connection.

## Where the data goes

- All data is stored **only in the user's browser** (`chrome.storage.local` and `localStorage`).
- Data is exchanged **only with the user's own Salesforce Marketing Cloud instance** (`*.exacttarget.com` and `*.marketingcloudapis.com`), using read-only GET requests and, in "Installed Package" mode, the OAuth token request.
- There is **no MC Navigator server**. The extension does not send data to the developer or to third parties, and it contains no analytics, advertising or tracking.
- The extension never creates, modifies or deletes anything in Marketing Cloud.
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

_Ultimo aggiornamento: 10 ottobre 2026_

MC Navigator è un'estensione di Chrome che aiuta chi usa Salesforce Marketing Cloud Engagement a esplorare i metadati della propria business unit (Data Extension, automation, query, script, journey, file import) e la lineage dei dati.

## Quali dati tratta l'estensione

- **Metadati di Marketing Cloud**: nomi, key e cartelle di Data Extension, automation, query, script, journey, import e attività sui file; codice SQL e degli script; campi delle Data Extension. Su richiesta esplicita dell'utente viene mostrata un'anteprima di massimo 50 righe di una Data Extension, che non viene salvata.
- **Impostazioni di connessione**: in modalità "Installed Package", Client ID, Client Secret, subdomain e MID inseriti dall'utente. In modalità "sessione di Marketing Cloud" non viene inserita né salvata alcuna credenziale: l'estensione usa la sessione già aperta nel browser.
- **Preferenze**: lingua dell'interfaccia, ultima scheda e connessione selezionate.

## Dove vanno i dati

- Tutti i dati sono salvati **solo nel browser dell'utente** (`chrome.storage.local` e `localStorage`).
- I dati vengono scambiati **solo con l'istanza Salesforce Marketing Cloud dell'utente** (`*.exacttarget.com` e `*.marketingcloudapis.com`), con richieste GET in sola lettura e, in modalità "Installed Package", con la richiesta del token OAuth.
- **Non esiste un server di MC Navigator**. L'estensione non invia dati allo sviluppatore né a terzi e non contiene analytics, pubblicità o tracciamento.
- L'estensione non crea, modifica né elimina nulla in Marketing Cloud.
- Gli export Excel vengono generati in locale e salvati solo dove sceglie l'utente.

## Conservazione e cancellazione

I dati restano nel browser finché l'utente non li elimina. Dalle Impostazioni si può svuotare l'indice locale o rimuovere una connessione, insieme alle sue credenziali e al suo indice. Disinstallando l'estensione vengono eliminati tutti i suoi dati.

## Sicurezza

In modalità "Installed Package" il Client Secret è salvato non cifrato nello storage dell'estensione. Si consiglia di usare un Installed Package dedicato con permessi di sola lettura, oppure la modalità "sessione di Marketing Cloud", che non salva credenziali.

## Modifiche e contatti

Le modifiche a questa informativa saranno pubblicate in questa pagina. Per domande scrivi a: **fusi.danilo@gmail.com**.

MC Navigator è uno strumento indipendente, non affiliato, approvato o sponsorizzato da Salesforce, Inc. Salesforce e Marketing Cloud sono marchi di Salesforce, Inc.
