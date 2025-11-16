
# Reflexión adicional: Comparación conceptual

## 1️⃣ Manejo de ambigüedad y contradicciones
El flujo de trabajo multiagente maneja la ambigüedad y las contradicciones mediante la colaboración entre varios agentes especializados. Cada agente puede proponer soluciones, validar información y cuestionar inconsistencias. Esto permite debatir diferentes interpretaciones y llegar a una respuesta refinada, especialmente en problemas abiertos o mal definidos.

El enfoque RAG depende de la calidad de los documentos recuperados. Si estos contienen información contradictoria, el modelo puede reflejarla sin resolverla automáticamente. RAG es más literal y factual, pero no razona sobre ambigüedad de manera activa.

## 2️⃣ Veracidad y cobertura de recuperación de datos
RAG enfatiza la veracidad porque las respuestas se basan en documentos recuperados. La cobertura depende del corpus indexado: si algo no está en la base de datos, no será incluido. Los sistemas multiagente pueden generar respuestas más amplias, pero con mayor riesgo de errores o información no verificada.

## 3️⃣ Adecuación según tipo de pregunta
- Preguntas abiertas o exploratorias: flujo multiagente es más adecuado, permite síntesis, debate y razonamiento complejo.
- Preguntas basadas en hechos: RAG es preferible, reduce errores y asegura respuestas basadas en fuentes verificadas.

**Conclusión:** Multiagente → creatividad y razonamiento; RAG → precisión factual y cobertura de información.
