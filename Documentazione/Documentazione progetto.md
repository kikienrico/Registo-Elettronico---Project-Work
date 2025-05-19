# Documentazione del Progetto – Registro Scolastico

## Inizio Progetto
**Data di inizio:** 03/03/2025  
**Data di fine:** 11/04/2025  
**Partecipanti:** Sisti, Puppo, Enrico

Il 3 marzo 2025 è stato avviato ufficialmente il progetto "Registro Scolastico", con l'obiettivo di realizzare un software gestionale scolastico che permetta di amministrare in modo digitale i dati relativi a studenti, docenti, classi e voti. Il progetto è stato suddiviso in più fasi, con il supporto del diagramma di Gantt per la pianificazione delle attività.

---

## Analisi Requisiti
**Periodo:** 04/03/2025 – 07/03/2025  
**Attività:**  
- Raccolta dei requisiti funzionali e non funzionali.
- Studio del contesto scolastico e degli utenti coinvolti.
- Analisi delle specifiche tecniche e organizzative.
- Definizione dei ruoli e privilegi.

**Ruoli e Privilegi:**
- **Studente:** può visualizzare i propri dati (voti, orario, classi).
- **Docente:** può visualizzare e inserire voti.
- **Editor:** può creare e gestire utenti, ma non ha accesso ai voti.
- **Amministratore (Admin):** pieno accesso al sistema.

---

## ✅ Milestone 1 – Presentazione Bozzetti UI
**Periodo:** 08/03/2025 – 09/03/2025

Presentazione dei bozzetti delle interfacce grafiche per:
- Login
- Dashboard utente
- Visualizzazione voti
- Gestione utenti

---

## Progettazione UI
**Periodo:** 09/03/2025 – 13/03/2025

Attività svolte:
- Definizione dei flussi di navigazione.
- Scelta della struttura delle pagine.
- Progettazione responsiva.
- Uniformità estetica tra i diversi ruoli.

---

## ✅ Milestone 2 – Login Docenti
**Periodo:** 14/03/2025 – 17/03/2025

Realizzazione della prima versione della schermata di login:
- Funzionalità di autenticazione base.
- Controllo dell’identità dei docenti.
- Test iniziali di accesso differenziato.

---

## Sviluppo Backend
**Periodo:** 18/03/2025 – 27/03/2025  
**Attività:**
- Creazione della logica di autenticazione.
- Collegamento al database per il recupero e la scrittura dati.
- Implementazione API per frontend.

**Sotto-attività:**
- `18/03 – 20/03`: Sistema di login (Responsabile: Sisti, Enrico)
- `21/03 – 27/03`: Autenticazione e accesso ai dati (Responsabile: Puppo)

---

## Sviluppo Frontend
**Periodo:** 28/03/2025 – 03/04/2025  
**Attività:**
- Costruzione dell’interfaccia utente.
- Integrazione con le API backend.
- Navigazione protetta in base al ruolo.

**Dettagli:**
- `Accesso utenti`: 28/03 – 31/03
- `Interfaccia grafica navigabile`: 28/03 – 03/04  
**Responsabile:** Enrico, Sisti

---

## Progettazione Database
**Periodo:** 04/04/2025 – 05/04/2025

**Tabelle previste:**
- `Utenti`, `Studenti`, `Docenti`, `Classi`, `Materie`, `Voti`, `Credenziali Temporanee`

**Relazioni:**
- `Studenti` e `Docenti` collegati a `Utenti` tramite `id_utente`
- `Voti` legati a `Studenti` e `Materie` tramite chiavi esterne
- Associazione tabelle tramite ID univoci

**Responsabili:** Puppo, Enrico, Sisti

---

## Test e Debug
**Periodo:** 07/04/2025 – 09/04/2025

**Attività svolte:**
- Test funzionali (login, accesso ai dati, privilegi)
- Debug dell’interfaccia utente
- Verifica ruoli e autorizzazioni

**Sotto-attività:**
- `Verifica accessi`: 07/04 – 08/04 (Responsabile: Enrico)
- `Controllo interfaccia`: 07/04 – 09/04 (Responsabile: Puppo)

---

## ✅ Milestone Finale – Sistema Funzionante
**Periodo:** 10/04/2025 – 11/04/2025

Consegna e collaudo della prima versione completa del gestionale:
- Tutti i ruoli funzionano correttamente.
- Il database è operativo.
- La grafica è usabile e testata.
- Test superati.

---

## 📅 [Cronoprogramma](https://www.treccani.it/vocabolario/cronoprogramma_(Neologismi)/) 

| Fase                           | Inizio      | Fine        | Responsabili              |
|-------------------------------|-------------|-------------|----------------------------|
| Inizio Progetto               | 03/03/2025  | 03/03/2025  | Tutti                      |
| Analisi Requisiti           
<div style="border:1px solid #990000;padding-left:20px;margin:0 0 10px 0;">

<h4>A PHP Error was encounter