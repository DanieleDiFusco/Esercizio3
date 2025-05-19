# Esercizio 3 – Visualizzazione dati JSON in tabella HTML

Questo esercizio mostra come caricare un file JSON da GitHub e visualizzarne il contenuto in una tabella HTML usando JavaScript.

## 📁 File inclusi

### `dati.json`
Contiene un array di oggetti con informazioni anagrafiche.

Esempio:
```json
[
  {
    "nome": "Mario",
    "cognome": "Rossi",
    "età": 25,
    "città": "Roma"
  },
  {
    "nome": "Luisa",
    "cognome": "Bianchi",
    "età": 30,
    "città": "Milano"
  },
  {
    "nome": "Giovanni",
    "cognome": "Verdi",
    "età": 28,
    "città": "Napoli"
  }
]
```

### `index.html`
Un file HTML che usa JavaScript per:
- Caricare i dati dal file JSON ospitato su GitHub
- Creare una tabella HTML e visualizzare le informazioni

⚠️ Assicurati che il file `dati.json` sia pubblico e si trovi nella branch `main` della stessa repo, così il file HTML può accedervi correttamente.

## 🚀 Come usarlo

1. Clona la repo o scarica i file.
2. Apri `index.html` in un browser.
3. Il file caricherà `dati.json` automaticamente e mostrerà i dati in tabella.

## ✅ Tecnologie usate

- HTML5
- JavaScript (vanilla)
- GitHub come hosting del file JSON
