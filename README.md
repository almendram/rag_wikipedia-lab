# Tarea 2 — Resumen RAG basado en Wikipedia

## 🎯 Objetivo
Crear un sistema de **Resumen Mejorado con Recuperación de Información (RAG)** usando datos de Wikipedia de código abierto.  
Se utiliza **LangChain + ChromaDB + SentenceTransformers** para consultar, insertar y resumir contenido factual, sin coordinación multiagente.

---

## ⚙️ Dependencias
Se requiere **Python 3.10+** y las siguientes librerías:

```bash
pip install wikipedia-api==0.5.4
pip install sentence-transformers chromadb langchain transformers torch pandas
