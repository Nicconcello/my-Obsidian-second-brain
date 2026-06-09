# Integrazione dell'Intelligenza Artificiale Locale

Per assistermi nello studio senza inviare dati a server esterni, ho configurato un ecosistema IA decentralizzato all'interno del mio Obsidian.

## Hardware & Stack Tecnologico
- **CPU:** AMD Ryzen 5 5600G
- **RAM:** 16 GB DDR4
- **Engine:** Ollama (esecuzione offline)
- **Modello:** Llama 3.2 (3B Parametri)
- **Plugin di interconnessione:** Obsidian Copilot (v3.3.3)

## Ottimizzazione delle Risorse (RAM/CPU Management)
Data l'assenza temporanea di una GPU dedicata e il tetto di 16GB di RAM di sistema, ho applicato le seguenti ottimizzazioni per garantire risposte rapide sotto i 10 secondi ed evitare colli di bottiglia prestazionali:

1. **Bypass della Ricerca Semantica:** Disattivazione delle funzioni di embedding vettoriale locali (RAG pesanti), sostituite da un sistema di **Keyword Matching testuale** nativo sul Vault per l'estrazione dei documenti pertinenti.
2. **Contesto Dinamico:** Limitazione della finestra di contesto (`num_ctx`) a **4096 token** per prevenire il sovraccarico della memoria volatile (RAM) durante sessioni di chat prolungate.
3. **Modalità di default:** Configurazione nativa in *Vault QA (free)* per indicizzare ed interrogare selettivamente solo le note attive, escludendo le cartelle di archivio storico tramite regole di esclusione personalizzate.
