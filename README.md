# 🏫 Classroom Planner Pro

**Strumento web per la gestione visiva della disposizione dei banchi in classe.**  
Progettato per insegnanti, funziona su qualsiasi browser — PC, LIM Android, tablet e smartphone.

---

## ✨ Funzionalità

- 🗺️ **Griglia interattiva 8×8** per disporre banchi, cattedra e corridoi
- 👤 **Assegnazione alunni** ai banchi tramite elenco o nome manuale
- 🔀 **Drag & Drop** per spostare i banchi — funziona sia su desktop (mouse) che su **LIM e dispositivi touch** (dito)
- 🎲 **Distribuzione casuale** degli alunni sui banchi disponibili
- 💾 **Salvataggio automatico** nel browser (localStorage) — i dati restano anche chiudendo la pagina
- 📂 **Gestione di più classi** — puoi creare, rinominare ed eliminare classi separate
- 📤 **Esporta / Importa JSON** — per fare backup o trasferire la disposizione su un altro dispositivo
- 🖨️ **Stampa / Salva PDF** — genera automaticamente un layout ottimizzato per foglio A4

---

## 🚀 Come si usa

### 1. Aprire l'applicazione
Apri il file `index.html` in qualsiasi browser moderno (Chrome, Firefox, Safari, Edge).  
Non richiede installazione, server o connessione a internet.

Puoi utilizzarlo anche online qui: https://superscuola.com/classe

### 2. Creare la griglia
- Fai clic su una **cella vuota** per aggiungere un banco
- Nel modale che appare puoi:
  - assegnare un alunno dall'elenco
  - digitare un nome personalizzato (es. *Sostegno*, *Cattedra*)
  - eliminare il banco

### 3. Inserire l'elenco alunni
Incolla i nomi nella casella di testo separandoli con `;`  
Esempio: `ROSSI MARIO; BIANCHI LUCIA; VERDI ANNA`

### 4. Distribuire automaticamente
Clicca **"Distribuisci Alunni"** per assegnare casualmente tutti gli alunni ai banchi disponibili.

### 5. Spostare i banchi (Drag & Drop)
- **Mouse (PC/Mac):** tieni premuto e trascina
- **Dito (LIM / tablet / smartphone):** tieni premuto il banco, trascinalo sulla posizione desiderata e alza il dito

### 6. Gestire più classi
Usa il menu a tendina in alto per passare da una classe all'altra.  
Con i pulsanti accanto puoi aggiungere ➕, rinominare ✏️ o eliminare 🗑️ una classe.

### 7. Backup e ripristino
- **Esporta JSON** → salva un file con tutta la disposizione
- **Importa JSON** → ripristina una disposizione salvata in precedenza (utile per trasferirla su un altro PC o recuperarla dopo aver svuotato la cache)

### 8. Stampa / PDF
Clicca **"Stampa / Salva PDF"**: la pagina si ottimizza automaticamente per il formato A4.  
Dal dialogo di stampa del browser scegli *"Salva come PDF"* per ottenere un file.

---

## 📱 Compatibilità

| Dispositivo | Supporto |
|---|---|
| PC Windows / Mac | ✅ Completo |
| LIM con Android | ✅ Touch drag & drop |
| iPad / iPhone | ✅ Touch drag & drop |
| Tablet Android | ✅ Touch drag & drop |
| Browser consigliati | Chrome, Edge, Firefox, Safari |

---

## 🗂️ Struttura del progetto

```
classroom-planner/
│
├── index.html      # Tutta l'applicazione (HTML + CSS + JS in un unico file)
├── README.md       # Questo file
└── LICENSE         # Licenza CC BY-NC-SA 4.0
```

L'applicazione è **monolitica per scelta**: un solo file `index.html` che non richiede dipendenze esterne, server o build tools. Basta aprirlo.

---

## 📜 Licenza

Quest'opera è distribuita con licenza  
**Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale**  
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.it)

Puoi liberamente:
- ✅ **Condividere** — copiare e ridistribuire il materiale
- ✅ **Adattare** — modificare e creare opere derivate

A queste condizioni:
- 📛 **Attribuzione** — devi citare l'autore originale
- 🚫 **Non commerciale** — non puoi usarlo per scopi commerciali
- 🔄 **Stessa licenza** — le opere derivate devono usare la stessa licenza

---

## 👤 Autore

**Sebastiano Basile**  
📬 Telegram: [sostegno.t.me](https://t.me/sostegno)  
💻 GitHub: [github.com/sebastianobasile](https://github.com/sebastianobasile?tab=repositories)
