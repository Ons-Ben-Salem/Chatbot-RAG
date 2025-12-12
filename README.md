# 🤖 RAG Chatbot

Prototype académique d’un **chatbot RAG (Retrieval-Augmented Generation)** permettant de répondre à des questions à partir de **documents locaux** grâce à la **recherche sémantique** et à un **LLM (Gemini)**.

---

##  Technologies
- Python
- PostgreSQL + pgvector
- Transformers (BGE embeddings)
- Gemini LLM

---

##  Données
- Dossier : `data/TRAIN_TXT`
- Type utilisé : `.txt`
- Découpage en chunks de **1000 caractères**

---

##  Fonctionnement
1. Vectorisation des documents
2. Stockage des embeddings en base
3. Recherche des documents pertinents
4. Génération de la réponse avec Gemini



