# 🕵️‍♂️ Instagram Unfollowers Scanner (Dark Minimal Edition)

![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?style=flat-square)
![Style](https://img.shields.io/badge/Style-Dark%20Mode-black?style=flat-square)

Uno script JavaScript leggero, sicuro e privo di dipendenze esterne per analizzare il tuo profilo Instagram e generare una lista di utenti che non ricambiano il follow ("Unfollowers").

> **Nota:** Questa versione è stata completamente ridisegnata per essere minimalista. Nessuna immagine, nessuna checkbox, nessuna automazione rischiosa. Solo dati puri in una "console-like" interface.

---

## ✨ Caratteristiche

* **🌑 Interfaccia "Terminal Style":** Un layout scuro (`#0a0a0a`) pulito e professionale, ispirato agli ambienti di sviluppo, per non affaticare la vista.
* **⚡ Ultra Leggero:** Rimosso il caricamento delle immagini profilo e dei badge inutili. La scansione è molto più veloce e leggera sulla memoria.
* **📜 Lista Continua:** Visualizzazione in un'unica lista numerata scrollabile. Niente più paginazione frammentata.
* **🛡️ Sicurezza Prima di Tutto:**
    * **Nessun Login Richiesto:** Sfrutta la sessione del browser già attiva. Le tue password non lasciano mai il tuo PC.
    * **No Auto-Unfollow:** Rimossa ogni funzione di automazione (unfollow di massa) per proteggere l'account da blocchi o restrizioni di Instagram.

---

## 🚀 Come Usarlo

Non serve installare nulla. Lo script gira direttamente nel tuo browser.

1. Vai su [Instagram.com](https://www.instagram.com/) ed effettua il login al tuo account.
2. Apri gli **Strumenti per Sviluppatori** del browser:
    * Premi `F12` sulla tastiera.
    * *Oppure* Tasto Destro del mouse in un punto qualsiasi della pagina -> **Ispeziona**.
3. Clicca sulla scheda **Console**.
4. Copia l'intero codice dello script (dal file `.js` di questo repository).
5. Incolla il codice nella Console e premi **Invio**.
6. Apparirà un pulsante **SCAN** al centro dello schermo. Cliccalo per avviare l'analisi.

---

## 🛠️ Anteprima

L'interfaccia si sovrappone alla pagina di Instagram mostrando:
1. Una barra di stato con il conteggio in tempo reale.
2. Una lista semplice e pulita: `#username`.

---

## 🔒 Privacy e Sicurezza

A differenza delle estensioni di Chrome o delle app di terze parti:
* **Questo script è Open Source:** Puoi leggere ogni riga di codice per vedere esattamente cosa fa.
* **Nessun dato viene inviato a server esterni:** Tutto avviene localmente (`Client-Side`) sul tuo browser.
* **Nessuna API nascosta:** Utilizza le chiamate GraphQL standard di Instagram che il tuo browser fa normalmente.

---

## ⚠️ Disclaimer

Questo progetto è sviluppato esclusivamente a scopo **educativo e di ricerca**.
L'uso di script automatizzati su Instagram potrebbe violare i Termini di Servizio della piattaforma. Anche se questo script è progettato per essere "passivo" (sola lettura) e include ritardi di sicurezza per evitare il rate-limiting, l'autore non si assume alcuna responsabilità per eventuali limitazioni temporanee o blocchi dell'account derivanti dal suo utilizzo.

**Usa lo script con buon senso.**
