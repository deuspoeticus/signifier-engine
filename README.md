# The Signifier Engine

> A RAG-based prompt generator utilizing a curated knowledge base of semiotics, art history, and technical cinematography.

[Access the active Notebook here](https://notebooklm.google.com/notebook/6e66dc21-51b3-4cf8-83f4-fcf9b90b0aff)

The Signifier Engine synthesizes conceptual inputs into structured JSON payloads optimized for image generation with Nano Banana Pro. By leveraging custom NotebookLM functionality, it processes queries through a deep, aesthetic, and structural lens.

## Structure

The engine's knowledge base is divided into three core pillars:

### `/sources`
The foundational texts. This directory contains the literary, theoretical, and technical works that form the core RAG corpus:
- Works on digital art and cinematography (Christiane Paul, Andrey Tarkovsky)
- Seminal literature prioritizing aesthetic structuralism (Baudelaire, Kafka, Poe, Dostoevsky, Dickinson)

### `/guides`
Instructional and structured formats. Contains parsing rules, negative dictionaries, and master prompts that dictate how the NotebookLM instance should interpret the sources and generate its output:
- Master prompts and system instructions (`MASTER_PROMPT`, `notebooklm-prompt.md`)
- Aesthetic definitions (`AESTHETICS_LIST.md`, `AESTHETICS_SHEET.csv`)
- Directives for formatting outputs (`prompting-guide.md`, `negative-dictionary.md`)

### `/docs`
Supplementary documentation and research outlines specific to different output modalities:
- Image Generation
- Video

---
*Synthesized for Nano Banana Pro.*
