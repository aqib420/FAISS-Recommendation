# FAISS-Recommendation

# 🎯 Event Recommendation System using FAISS and Sentence Transformers

An efficient, scalable content-based event recommendation system. It fetches event data from a **Supabase PostgreSQL database**, encodes the event content using **Sentence Transformers**, and builds a **FAISS vector index** to allow real-time semantic similarity search.

---

## 📌 Overview

This notebook builds a semantic search engine that recommends similar events based on event title, description, and tags. It is built for event marketplaces, ticketing platforms, or discovery apps.

---

## 🧠 Tech Stack

| Tool / Library        | Purpose                         |
| --------------------- | ------------------------------- |
| Supabase (PostgreSQL) | Event data backend              |
| psycopg2-binary       | Secure DB connection            |
| sentence-transformers | Text embedding generation       |
| FAISS                 | Fast vector similarity search   |
| pandas / NumPy        | Data manipulation               |
| python-dotenv         | Environment variable management |

---

## ⚙️ How to Run the Project (Start to Finish)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/aqib420/FAISS-Recommendation.git
cd FAISS-Recommendation

```
