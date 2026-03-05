# 🏥 Scheda Unica di Intervento Intraospedaliero - MET

![Versione](https://img.shields.io/badge/Versione-4.3_R._Print_Update-00A950)
![Licenza](https://img.shields.io/badge/Licenza-CC_BY--NC--ND_4.0-lightgrey)
![Utilizzo](https://img.shields.io/badge/Ambito-AOU_Careggi-blue)

Questa applicazione web-based è uno strumento digitale avanzato progettato per la **Centrale Operativa Sanitaria (COS)** e il **Medical Emergency Team (MET)** dell'Azienda Ospedaliero Universitaria Careggi. Il sistema permette la gestione rapida e la standardizzazione della documentazione clinica durante le emergenze intraospedaliere.

---

## ✨ Caratteristiche Principali

* **Calcolo Interattivo NEWS 2**: Sistema integrato per il calcolo automatico del *National Early Warning Score 2*, con supporto dinamico per Scala 1 e Scala 2 (pazienti con insufficienza respiratoria ipercapnica).
* **Monitoraggio Shock Index**: Calcolo automatico del rapporto tra Frequenza Cardiaca e Pressione Arteriosa Sistolica (FC/PAS) per l'identificazione precoce dello shock.
* **Ottimizzazione per la Stampa**: Layout CSS `@media print` progettato specificamente per generare un documento A4 professionale su due pagine, eliminando elementi di interfaccia non necessari.
* **Gestione Rivalutazioni**: Sezioni dedicate per il confronto dei parametri vitali tra l'attivazione, l'arrivo del team e la fine dell'intervento.
* **User Interface Protetta**: Sistema di prevenzione della selezione del testo e menu contestuale disabilitato per garantire l'integrità dei dati durante la compilazione.

---

## 🛠️ Specifiche Tecniche

* **Linguaggi**: HTML5, CSS3, JavaScript (Vanilla JS).
* **Peculiarità**: Nessuna dipendenza esterna (no jQuery o framework pesanti) per garantire la massima velocità di caricamento.
* **Logica Clinica**: Implementazione rigorosa degli algoritmi di scoring NEWS 2 basati sui range fisiologici standard.

---

## 📋 Struttura della Scheda

1.  **Identificazione**: Dati anagrafici e calcolo automatico dell'età.
2.  **Dettagli Chiamata**: Tipologia di emergenza (2222, Toscana Soccorso, Pegaso) e composizione del team.
3.  **Triage e Segni Vitali**: Tabella NEWS 2 con evidenziazione cromatica dei rischi (Low, Medium, High).
4.  **Valutazione Clinica**: Diagnosi medica sospetta e check-list dei segni e sintomi rilevati.
5.  **Trattamenti**: Registro degli interventi eseguiti (RCP, Ventilazione, Accessi venosi, Farmaci).
6.  **Esito**: Conclusione dell'intervento, destinazione del paziente e firme digitali/manuali.

---

## 🚀 Guida all'uso

1.  Aprire il file `Scheda Intervento Unico - MET.html` in un browser.
2.  Compilare i campi anagrafici e i parametri vitali; il sistema aggiornerà i punteggi di rischio in tempo reale.
3.  Utilizzare il tasto **"Stampa Scheda Completa"** per generare il PDF o inviare il documento alla stampante di reparto.
4.  È possibile utilizzare il tasto **"Salva Dati (JSON)"** per esportare i dati inseriti.

---

## 📄 Licenza e Crediti

Il progetto è protetto da licenza **Creative Commons Attribuzione - Non commerciale - Non opere derivate 4.0 Internazionale (CC BY-NC-ND 4.0)**.

* **Autore**: Inf. Giovanni Nonominato.
* **Copyright**: © 2026 - Tutti i diritti riservati - AUOC Careggi.

---
*Documento generato per il supporto alle attività del Team Emergenza Medica (MET).*
