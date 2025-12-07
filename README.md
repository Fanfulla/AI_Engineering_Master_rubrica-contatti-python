# 📱 Rubrica Contatti Python

> **Primo progetto completo in Python** - Sistema di gestione contatti sviluppato come progetto finale per il Master in AI Engineering.
---
## 📖 Descrizione

Questo è il mio **primo progetto Python completo**, realizzato come esercitazione finale del corso di programmazione Python del Master in AI Engineering con [Profession AI](https://profession.ai/).

Il progetto implementa un sistema di gestione contatti da terminale, con tutte le funzionalità CRUD (Create, Read, Update, Delete) e persistenza dei dati su file JSON.

**Nota importante:** Questo progetto rappresenta il mio percorso di apprendimento. Non è perfetto, ma sono orgoglioso del risultato perché mi ha permesso di consolidare tutti i concetti fondamentali della programmazione orientata agli oggetti in Python! 🎯
---

## ✨ Funzionalità implementate

- ➕ **Aggiunta contatti** - Nome, cognome, numero di telefono (obbligatori) + email e note (opzionali)
- 📋 **Visualizzazione completa** - Lista di tutti i contatti salvati
- 🔍 **Ricerca intelligente** - Cerca contatti per nome, cognome o numero di telefono
- ✏️ **Modifica contatti** - Aggiorna qualsiasi campo di un contatto esistente
- 🗑️ **Eliminazione con conferma** - Rimuovi contatti dalla rubrica in sicurezza
- 💾 **Persistenza automatica** - Salvataggio su file JSON dopo ogni operazione

---

## 🛠️ Tecnologie e concetti applicati

- **Python 3** - Linguaggio di programmazione
- **Programmazione Orientata agli Oggetti (OOP)**
  - Classi: `Contatto` e `Rubrica`
  - Metodi speciali: `__init__`, `__str__`
  - Encapsulation e modularità
- **Gestione file JSON** - Per la persistenza dei dati
- **Gestione errori** - Try/except per validazione input utente
- **User Experience** - Menu interattivo, messaggi di conferma, feedback utente
- **Google Colab** - Ambiente di sviluppo

---

## 📂 Struttura del codice

Il progetto è organizzato in due classi principali:

### Classe `Contatto`
Rappresenta un singolo contatto con i suoi attributi (nome, cognome, numero, email, note) e metodi per la gestione e visualizzazione.

### Classe `Rubrica`
Gestisce l'insieme dei contatti e implementa tutte le operazioni:
- `aggiungi_contatto()` - Aggiunta nuovi contatti
- `visualizza_tutti()` - Visualizzazione completa
- `visualizza_contatto()` - Ricerca
- `modifica_contatto()` - Modifica dati
- `elimina_contatto()` - Eliminazione
- `salva_file()` - Salvataggio su JSON
- `carica_rubrica()` - Caricamento automatico all'avvio

### Menu principale
Interfaccia utente interattiva con gestione errori e validazione input.

---

## 🚀 Come utilizzare

### Opzione 1: Google Colab (consigliata)
Clicca sul badge "Open in Colab" qui sopra e esegui tutte le celle del notebook.

### Opzione 2: Locale
1. Scarica il file `.ipynb`
2. Apri in Jupyter Notebook o Google Colab
3. Esegui tutte le celle
4. Interagisci con il menu per gestire i tuoi contatti!

---

## 📚 Cosa ho imparato

Questo progetto mi ha permesso di consolidare:

- ✅ Concetti di **OOP** (classi, oggetti, attributi, metodi, `self`)
- ✅ Gestione di **strutture dati** (liste, dizionari)
- ✅ **Serializzazione** con JSON (conversione oggetti ↔ dizionari)
- ✅ **File I/O** (lettura e scrittura file)
- ✅ **Control flow** (if/elif/else, while, for, try/except)
- ✅ **Validazione input** utente
- ✅ Pensiero da **programmatore** (debugging, problem solving, refactoring)

---

## 🎓 Contesto accademico

**Master:** AI Engineering  
**Istituto:** Profession AI  
**Progetto:** Esercitazione finale Python - Programmazione Orientata agli Oggetti  
**Data completamento:** Dicembre 2024  
**Valutazione:** ✅ Superato

---

## 💭 Riflessioni

Questo è stato il mio primo progetto completo in Python. Ci sono sicuramente aspetti che potrei migliorare (gestione avanzata delle eccezioni, testing, interfaccia grafica, ecc.), ma sono fiero di quello che ho costruito partendo da zero.

Il progetto rappresenta un punto di partenza importante nel mio percorso di apprendimento della programmazione! 🌱

---

## 👨‍💻 Autore

**Salvatore (SA)**  
GitHub: [@Fanfulla](https://github.com/Fanfulla)

*Studente del Master in AI Engineering - Profession AI*

---

## 📄 Licenza

MIT License - Sentiti libero di utilizzare questo codice per imparare!

---

## 🙏 Ringraziamenti

Grazie a Profession AI per il percorso formativo e a tutti coloro che mi hanno supportato in questo viaggio di apprendimento! 💪

---

⭐ **Se questo progetto ti è stato utile per imparare Python, lascia una stella!**
