# 📋 HTML First Exam - Survey Form

Questo progetto fa parte della certificazione **Responsive Web Design** di **freeCodeCamp**. L'obiettivo principale è stato la realizzazione di un modulo di sondaggio (*Survey Form*) strutturato interamente in HTML5 semantico, progettato per raccogliere input dagli utenti e superare tutti i test di validazione automatica.

---

## 🚀 Caratteristiche e Requisiti Implementati

Il modulo gestisce correttamente diversi tipi di campi ed elementi interattivi:
* **Struttura HTML5 Semantica**: Uso di tag standard tra cui `<h1>`, `<p>`, `<form>`, `<label>`, `<input>`, `<select>` e `<textarea>`.
* **Validazione dei Campi**: 
  * Campi obbligatori (`required`) per nome ed email.
  * Controllo nativo del browser per gli indirizzi email (`type="email"`).
  * Campo numerico vincolato da un intervallo specifico tramite gli attributi `min` e `max`.
* **Scelte e Opzioni**:
  * Menu a tendina (`<select>`) con opzioni dedicate.
  * Pulsanti di scelta singola (*Radio Buttons*) raggruppati logicamente tramite l'attributo `name`.
  * Caselle di spunta (*Checkboxes*) per la selezione multipla delle preferenze.
* **Invio dei Dati**: Pulsante di invio dedicato dotato dell'attributo `id="submit"`.

---

## 📁 Struttura del Progetto

```text
└── index.html       # File principale con la struttura completa del form
