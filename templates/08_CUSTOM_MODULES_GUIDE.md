# 🧩 CUSTOM MODULES GUIDE / GUIDA MODULI PERSONALIZZATI
**Methodology / Metodologia**: Sentinel-MD Extensibility
**Status**: Active / Attivo

---

## 🎯 PURPOSE / SCOPO
Sentinel-MD is modular. While the first 7 files are the "Core Engine", you can create custom files (from #08 to #17) to fit your specific project needs.
Sentinel-MD è modulare. Mentre i primi 7 file sono il "Motore Core", puoi creare file personalizzati (dal #08 al #17) per adattarli alle esigenze specifiche del tuo progetto.

---

## 🛠️ HOW TO CREATE A NEW MODULE / COME CREARE UN NUOVO MODULO
To ensure the AI respects a new file, follow this **Sentinel Structure**:
Per garantire che l'IA rispetti un nuovo file, segui questa **Struttura Sentinel**:

1. **Header / Intestazione**: Title, Version, and Scope / Titolo, Versione e Scopo.
2. **Rules / Regole**: Specific constraints for the AI regarding this file / Vincoli specifici per l'IA relativi a questo file.
3. **Data/Content / Dati/Contenuto**: The actual technical information / Le informazioni tecniche vere e proprie.
4. **Sync Rule / Regola di Sincronizzazione**: When and how the AI must update it / Quando e come l'IA deve aggiornarlo.

---

## 💡 EXAMPLES OF CUSTOM FILES / ESEMPI DI FILE PERSONALIZZATI
*You can implement these based on your stack / Puoi implementarli in base al tuo stack:*

- **API_CONTRACTS.md**: For FastAPI/REST documentation / Per documentazione FastAPI/REST.
- **DATABASE_SCHEMA.md**: For SQL/NoSQL structures / Per strutture SQL/NoSQL.
- **PROD_DEPLOY_CHECKLIST.md**: For DevOps and CI/CD rules / Per regole DevOps e CI/CD.
- **UI_DASHBOARD_SPECS.md**: For frontend components / Per componenti frontend.
- **RESEARCH_LOGS.md**: For experimental AI tests / Per test sperimentali dell'IA.

---

## 🧭 INTEGRATION RULE / REGOLA DI INTEGRAZIONE
> **[IMPORTANT]**: Every time you add a new file, you MUST update the **Official Index** in `01_MASTER_DOCUMENT.md`. Otherwise, the AI might ignore it.
> **[IMPORTANTE]**: Ogni volta che aggiungi un nuovo file, DEVI aggiornare l'**Indice Ufficiale** nel `01_MASTER_DOCUMENT.md`. Altrimenti, l'IA potrebbe ignorarlo.

---
**AI Instruction / Istruzione per l'IA**: 
"If you detect a file starting with a number from 08 to 17 that is not in the index, notify the user and ask for its integration rules."
"Se rilevi un file che inizia con un numero da 08 a 17 non presente nell'indice, avvisa l'utente e chiedi le sue regole di integrazione."
