# TDWI 2025 - Hands-On RAG workshop
Repository für meinen Hands-On RAG workshop während TDWI Konferenz 2025:💻 **Codieren statt Folieren!**

Lust auf einen Hands-On-Workshop zu Retrieval-Augmented Generation auf der TDWI 2025 (München, 24.–26. Juni)?

Was dich in meinem Beispiel-Notebook erwartet:
- 🧹Daten laden & reinigen – denn ohne Qualität läuft mal wieder nix
- ✂️Chunking – den Elefanten in Scheiben schneiden
- 🧮Embedding – die Welt in Vektoren gießen
- 🗄️Vector Store – Mathe statt Magie rund um FAISS, DuckDB, PostgreSQL
- 🌀Prompt pimpen – Quellen smart einbauen
- 🪄Chat GPTiert – Kontext drin, Halluzinationen draußen!?


Ziel ist es, ein Verständnis dafür zu entwickeln, wie sich Large Language Models mit externem Wissen kombinieren lassen, und wie man eine solche Architektur aufbaut, anpasst und sinnvoll einsetzt.

Voraussetzungen
- Python-Kenntnisse
- Google Colab (frei verfügbare Notebook Umgebung https://colab.research.google.com/)
- HuggingFace-Account https://huggingface.co/ und LLM wie Gemini https://aistudio.google.com/apikey (jeweils ohne Kosten)
- Optional OpenAI-Account (API Guthaben notwendig, kostenpflichtig)

Colab Umgebung mit hinterlegten Secrets und hochgeladener requirements.txt. Das Notebook befindet sich im Order src.
![image](https://github.com/user-attachments/assets/118c3e63-9275-41c2-8400-eb4c42ae804e)


Zusätzliche Voraussetzungen bei lokaler Ausführung
- Python ≥ 3.11
- Erste Schritte mit Jupyter Notebooks
- pip install -r requirements.txt für die lokale Python Umgebung oder zumindest jupyter notebook installieren, da requirements.txt aus dem Notebook geladen und installiert wird
- .env anlegen mit den im obigen Screenshot aufgeführten Schlüsseln (Secrets)
- Falls PostgreSQL pgvector genutzt werden soll: lokale Docker/podman Installation

Siehe auch Blog Artikel [From Raw Text to Ready Answers — A Technical Deep-Dive into Retrieval-Augmented Generation (RAG)](https://buckenhofer.com/2025/06/from-raw-text-to-ready-answers-a-technical-deep-dive-into-retrieval-augmented-generation-rag/).

![image](https://github.com/user-attachments/assets/995e8b98-6dfa-4639-ad31-d94e918b35f4)

