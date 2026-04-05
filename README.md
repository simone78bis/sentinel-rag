# 🛡️ Sentinel-MD: Deterministic Context Methodology

[ [English Version](#english-version) | [Versione Italiana](#versione-italiana) ]

---

<a name="versione-italiana"></a>
# 🇮🇹 VERSIONE ITALIANA

## 🎯 Visione Strategica
**Sentinel-MD** non è un software, ma un **framework metodologico** di gestione del contesto per lo sviluppo assistito da IA (LLM). 

Il problema principale degli LLM moderni (Claude, Llama, Qwen) è la perdita di coerenza su sessioni lunghe e la tendenza a sovrascrivere o ignorare regole architettoniche. Sentinel-MD risolve questo problema spostando la "Memoria di Lavoro" dal contesto volatile dell'IA a una **struttura rigida di file Markdown (17 documenti)**.

## 🕰️ Provenance & Prior Art (Originalità 2025)
Questa metodologia è stata creata e perfezionata nel corso del **2025** per gestire progetti complessi su hardware locale (RTX 5070), anticipando le attuali soluzioni commerciali di "coding agents".
- **Validazione Storica**: Consulta la cartella [`/proofs`](./proofs) per gli screenshot dei filesystem con timestamp originali.

## 🧠 L'Ontologia Sentinel (I 17 Pilastri)
La metodologia si basa sull'uso di 17 file MD interdipendenti che fungono da **Ancora di Verità** per l'IA:

1.  **MASTER_DOCUMENT**: La "Costituzione". Contiene le Golden Rules e l'indice di progetto.
2.  **SOLUTION_ARCHITECTURE**: Definisce i layer e la logica di comunicazione.
3.  **DATABASE_SCHEMA**: Mappa le entità per evitare allucinazioni sui dati.
4.  **SERVICES_INDEX**: Catalogo dei componenti esistenti (per evitare duplicazioni).
5.  **TASK_APERTI**: Il "punto di contatto" dinamico tra utente e IA.
6.  **NEXT_SESSION_START**: Il ponte temporale per riprendere il lavoro senza "amnesia".
7.  **CHANGELOG_DETAILED**: La cronologia atomica delle decisioni prese.
*... (Vedi la lista completa nei template)*

## ⚖️ Le Golden Rules Universali
Il cuore della metodologia è l'imposizione di vincoli deterministici:
- **NO ESCAPISM**: Divieto di produrre codice non tracciato nei documenti ufficiali.
- **INTEGRITY FIRST**: L'IA non può "riassumere" il codice; deve garantire la completezza.
- **PATH DETERMINISM**: Uso obbligatorio di percorsi assoluti per la riproducibilità.
- **CONTEXT SYNC**: Obbligo di aggiornare la documentazione MD *prima* di chiudere la sessione.

---

<a name="english-version"></a>
# 🇺🇸 ENGLISH VERSION

## 🎯 Strategic Vision
**Sentinel-MD** is a **methodological framework** designed to provide deterministic context management for AI-assisted development. It prevents "context drift" by anchoring the AI's workspace to a structured set of 17 Markdown files.

## 🧠 The Sentinel Ontology
The methodology shifts the "Single Source of Truth" to an external, human-readable structure:
- **MASTER_DOCUMENT**: The core project constitution and ruleset.
- **TASK_APERTI**: A dynamic bridge for tracking current operations.
- **NEXT_SESSION_START**: A persistence layer for seamless session handovers.

## ⚖️ Core Principles
- **NO ESCAPISM**: No undocumented code changes allowed.
- **DETERMINISTIC SYNC**: Documentation must be updated by the AI after every task.
- **CONTEXT PERSISTENCE**: Ensuring the AI "remembers" the architecture through external files, not internal weights.

---

## 🛠️ How to Implement
1. Clone this repository.
2. Adapt the [`/templates`](./templates) to your project needs.
3. Use the **Master Prompt** (provided in docs) to initialize your AI agent.
4. Maintain the "Documentation-First" loop.

## 📜 License
Distributed under MIT License. See `LICENSE` for details.
