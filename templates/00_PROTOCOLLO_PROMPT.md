# ⚡ SENTINEL-MD: OPERATIONAL PROMPTS / PROMPT OPERATIVI

This file contains the exact prompts used to activate and close the Sentinel-MD methodology.
Questo file contiene i prompt esatti utilizzati per attivare e chiudere la metodologia Sentinel-MD.

---

## 🟢 START SESSION / INIZIO SESSIONE
*Copy and paste this prompt to initialize the AI with the Master Document and check the status.*
*Copia e incolla questo prompt per inizializzare l'IA con il Master Document e verificare lo stato.*

> **PROMPT:**
> "Stiamo facendo debug alla soluzione #file:'[PATH_TO_MASTER_DOCUMENT_V2.md]', quali task abbiamo in programma?"
> "We are debugging the solution #file:'[PATH_TO_MASTER_DOCUMENT_V2.md]', what tasks do we have scheduled?"

---

## 🔴 END SESSION / FINE SESSIONE
*Copy and paste this prompt to ensure the AI synchronizes all documentation before closing.*
*Copia e incolla questo prompt per garantire che l'IA sincronizzi tutta la documentazione prima di chiudere.*

> **PROMPT:**
> "Ottimo, ora aggiorniamo tutti i documenti ufficiali."
> "Great, now let's update all official documents."

---

## 🧭 USAGE NOTES / NOTE D'USO
- **Consistency**: These prompts ensure the AI remains anchored to the 17-file structure.
- **Consistenza**: Questi prompt garantiscono che l'IA rimanga ancorata alla struttura dei 17 file.
- **Automation**: The AI is expected to check `05_TASK_APERTI.md` and `06_NEXT_SESSION_START.md` automatically upon the start prompt.
- **Automazione**: L'IA deve controllare automaticamente `05_TASK_APERTI.md` e `06_NEXT_SESSION_START.md` al prompt di inizio.
