[English](#english) · [Español](#español)

---

## English

### David Camacho

**Head of Data Intelligence** at [Celestial Dynamics](https://celestialdynamics.io) since July 2026, after ten months as AI Architect. Mathematician from UNAM (Faculty of Sciences). I work at the intersection of mathematical rigor and production-grade AI engineering — knowledge graphs, retrieval-augmented generation, and inference infrastructure running on-premise.

I lead a team of five and set the reference architecture and priorities for five products and three cross-functional collaborations. I design systems and document them so that someone else can sustain them.

#### What I build

*The systems below are closed-source, so they are described by function.*

**Geocontextual intelligence platform** — Knowledge-based GraphRAG (IR-KGQA) over a knowledge graph of 400M+ nodes and 1.2B+ edges, built from more than 20 data sources. Multi-signal retrieval: query-scope routing, multi-role LLM routing with stage-specialized models, weighted mixture of retrievers, and multi-space vector search (semantic, structural, functional). Every figure it returns is traceable to the graph path that produced it. Architect and author of 72% of the codebase; twelve production releases in eleven months, on Kubernetes over bare metal with an on-premise cluster of 8× NVIDIA H100 NVL.

> It is **not** a language model. The models are external and interchangeable — the territorial and demographic grounding lives in the data, not in the weights.

**Conversational voice platform for contact centers** — Multi-tenant by design: real-time STT, LLM orchestration, neural TTS and VoIP integration, running fully on-premise, with PII and prompt-injection guardrails. End-to-end owner — backend, frontend, tests and documentation — with the MVP delivered in three months. Voice-to-voice latency cut from ~5.4 s to 1.2 s p50, measured on production call records.

#### Public projects

**[ThoughtLink](https://github.com/DavidCamachoCD/thoughtlink)** — End-to-end pipeline that decodes non-invasive brain signals (EEG + TD-NIRS) into commands for a humanoid robot in MuJoCo. Two-stage hierarchical classifier — a rest/active gate plus a four-class decoder (RBF SVM, scikit-learn) — with a stability layer for confidence thresholding, hysteresis, debouncing and majority voting. Feature engineering across band power, Hjorth parameters and DWT wavelets, plus a PyTorch model zoo (EEGNet, temporal GRU) exported to ONNX for comparison. 283 unit tests. Built for the **Global AI Hackathon 2026** (Hack-Nation × Kernel × Dimensional), Challenge #9.

#### Stack

**Graph & data** — NebulaGraph · Neo4j · PostgreSQL/PostGIS · Milvus · Qdrant · Redis · LinkML · ETL  
**AI & inference** — GraphRAG · RAG · MCP · vLLM · SGLang · Ollama · LLM/SLM · PyTorch · scikit-learn · RAPIDS · NVIDIA AI Enterprise  
**Platform** — Python · FastAPI · React · TypeScript · OpenAPI · Kubernetes · Docker · CI/CD · Git · Claude Code · Linux

#### Certifications

Neo4j GraphAcademy (2022) — Certified Professional · Graph Data Science Certified · Neo4j 4.0 Certified

#### Contact

[LinkedIn](https://www.linkedin.com/in/david-camacho-bol) · david.camacho.052@gmail.com

---

## Español

### David Camacho

**Head of Data Intelligence** en [Celestial Dynamics](https://celestialdynamics.io) desde julio de 2026, tras diez meses como AI Architect. Matemático por la UNAM (Facultad de Ciencias). Trabajo en la intersección entre rigor matemático e ingeniería de IA en producción: knowledge graphs, recuperación aumentada por generación e infraestructura de inferencia *on-premise*.

Dirijo un equipo de cinco personas y defino la arquitectura de referencia y las prioridades de cinco productos y tres colaboraciones transversales. Diseño sistemas y los documento para que otra persona pueda sostenerlos.

#### Lo que construyo

*Los sistemas siguientes son de código cerrado, así que se describen por función.*

**Plataforma de inteligencia geocontextual** — *Knowledge-based GraphRAG* (IR-KGQA) sobre un grafo de conocimiento de +400M nodos y +1.2B conexiones, construido desde más de 20 fuentes de datos. Recuperación multi-señal: enrutamiento por alcance de consulta, *routing* multi-rol de LLM con modelos especializados por etapa, mezcla ponderada de recuperadores y búsqueda vectorial multiespacio (semántica, estructural y funcional). Cada cifra que devuelve es trazable al camino del grafo que la produjo. Arquitecto y autor del 72 % del código base; doce versiones en producción en once meses, sobre Kubernetes en *bare metal* con clúster *on-premise* de 8× NVIDIA H100 NVL.

> **No** es un modelo de lenguaje. Los modelos son externos e intercambiables: el anclaje territorial y demográfico vive en los datos, no en los pesos.

**Plataforma conversacional de voz para contact centers** — Multitenant por diseño: reconocimiento de voz en tiempo real, orquestación de LLMs, síntesis de voz neuronal e integración VoIP, en ejecución cien por ciento local, con *guardrails* de PII e inyección de *prompts*. Responsable de extremo a extremo —*backend*, *frontend*, pruebas y documentación—, con el MVP entregado en tres meses. Latencia voz a voz reducida de ~5.4 s a 1.2 s de p50, medida sobre registros de llamadas en producción.

#### Proyectos públicos

**[ThoughtLink](https://github.com/DavidCamachoCD/thoughtlink)** — Pipeline *end-to-end* que decodifica señales cerebrales no invasivas (EEG + TD-NIRS) en comandos para un robot humanoide en MuJoCo. Clasificador jerárquico de dos etapas —compuerta reposo/actividad más decodificador de cuatro clases (SVM RBF, scikit-learn)— con capa de estabilidad: umbral de confianza, histéresis, antirrebote y voto mayoritario. Ingeniería de características sobre potencia de banda, parámetros de Hjorth y wavelets DWT, más un zoológico de modelos en PyTorch (EEGNet, GRU temporal) exportados a ONNX para comparación. 283 pruebas unitarias. Construido para el **Global AI Hackathon 2026** (Hack-Nation × Kernel × Dimensional), Reto #9.

#### Stack

**Grafos y datos** — NebulaGraph · Neo4j · PostgreSQL/PostGIS · Milvus · Qdrant · Redis · LinkML · ETL  
**IA e inferencia** — GraphRAG · RAG · MCP · vLLM · SGLang · Ollama · LLM/SLM · PyTorch · scikit-learn · RAPIDS · NVIDIA AI Enterprise  
**Plataforma** — Python · FastAPI · React · TypeScript · OpenAPI · Kubernetes · Docker · CI/CD · Git · Claude Code · Linux

#### Certificaciones

Neo4j GraphAcademy (2022) — Certified Professional · Graph Data Science Certified · Neo4j 4.0 Certified

#### Contacto

[LinkedIn](https://www.linkedin.com/in/david-camacho-bol) · david.camacho.052@gmail.com
