# My Digital Second Brain & AI Knowledge System

Benvenuto nella repository del mio **Second Brain**. Questo spazio rappresenta l'ingegnerizzazione del mio metodo di studio, della mia produttività e della gestione delle mie conoscenze.

Il sistema è interamente sviluppato su **Obsidian**, sfruttando i principi del *Personal Knowledge Management* (PKM) e i collegamenti ipertestuali (backlink) per mappare i concetti in modo atomico, creando una vera e propria rete neurale di informazioni.

---

## Architettura del Vault

Per evitare il caos e ordinare il tutto, il mio Vault di Obsidian è suddiviso secondo una logica rigorosa che separa i flussi di lavoro, la teoria e l'archiviazione:

* **`1-Progetti`** – Progetti non ancora iniziati per mancanza di tempo, conoscenze o materiali, ma che sono completamente idealizzati.
* **`2-Aree`** – I punti di accesso centrali. Cartella divisa per materie d'esame (es. *Algoritmi & Strutture Dati*, *Reti e Internet*, *Intelligenza Artificiale*). Ogni nota qui fa da "hub" per i concetti correlati.
* **`3-Risorse`** – Il cuore pulsante del sistema. Note atomiche, cortissime e focalizzate su un unico concetto specifico (es. la definizione di *MaxHeap* o il funzionamento del *NAT*), interconnesse tra loro tramite link.
* **`4-Archive`** – Tutto ciò che è completato (vecchi progetti). Rimane nel database per essere consultato dall'IA, ma non disturba la navigazione quotidiana.
* **`5-Quotidiano`** – Il mio diario di giornaliero. Serve a tracciare i progressi quotidiani, i task da fare e a treacciare le mie abitudini
* **`6-Riflessioni`** - Una raccolta di pensieri e appunti che avvolgono diverse tematiche.

---

## Come questo sistema rivoluziona il mio metodo di studio

A differenza del classico studio passivo su quaderno o PDF lineari, Obsidian mi permette di attuare uno **studio attivo e associativo**:

1.  **Collegamento dei Concetti:** Se sto studiando il funzionamento del protocollo *PPO* nei modelli linguistici (IA) e questo si basa sul *Reinforcement Learning*, le due note sono collegate con un link. Quando ripasso un argomento, vedo automaticamente tutte le connessioni logiche nel grafo.
2.  **Apprendimento Incrementale:** Gli appunti evolvono con me. Posso iniziare scrivendo una nota parziale sull'*Heap Sort* e, settimane dopo, integrarla con un blocco di codice in C o con l'analisi della complessità computazionale senza rompere la struttura.
3.  **Grafico Interattivo:** Sfrutto la visualizzazione a grafo per identificare i "colli di bottiglia" del mio studio o le aree isolate, intervenendo per unire i concetti teorici alla pratica di laboratorio.

---

## Ecosistema IA Locale (Privacy & Performance)

Il mio database è potenziato da un'**Intelligenza Artificiale che gira al 100% in locale** sulla mia macchina, garantendo privacy assoluta e disponibilità offline.

* **Engine:** Ollama
* **Modello LLM:** Llama 3.2 (3B Parametri) – Ottimizzato per esecuzione su CPU
* **Integrazione:** Obsidian Copilot impostato in modalità *Vault QA*.

> 💡 **Ingegnerizzazione Hardware:** Avendo a disposizione una CPU AMD Ryzen 5 5600G e 16GB di RAM di sistema (senza GPU dedicata), ho ottimizzato i parametri software (contesto bloccato a 4096 token) per ottenere risposte rapide, evitando il freeze del sistema operativo.

---

## 🗺️ Contenuti Estratti in questa Repository

In questa repository ho voluto documentare la struttura del mio sistema attraverso due file chiave:
* 📋 **[Template di Studio Autentico](templates/algoritmo-template.md):** Lo schema reale che utilizzo per mappare concetti informatici (es. Heap Sort), mostrando come separo la logica e la teoria.
* 📄 **[Documentazione Tecnica IA](docs/ai-integration.md):** Le specifiche di configurazione e i dettagli di come ho ottimizzato Llama 3.2 a livello hardware sul mio PC.
