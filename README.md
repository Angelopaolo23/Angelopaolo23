# Angelo Paolo Bugueño Bugueño

**Fundador de Vista Tempesta · AI Engineer + Ingeniero en Negocios Internacionales** · Santiago, Chile

Diseño el objetivo y construyo el sistema: la estrategia y la implementación no se separan. En la mayoría de los proyectos de IA esas dos cosas son dos personas, y el valor se pierde en el traspaso.

> *"El contexto bien estructurado es la forma más alta de ingeniería."*

---

## 🔭 Qué estoy construyendo

### Vista Tempesta — tu manager de carrera en tech

Lee la historia completa de una persona y mide cada oferta contra su tiempo, sus fortalezas, sus valores y lo que la mueve. Enfocado primero en Chile. **Hoy en beta.**

Lo construí de punta a punta: producto, arquitectura, narrativa, precio e instrumentación.

- **Arquitectura híbrida bajo un principio explícito — el modelo clasifica, el código calcula**: motor de scoring determinista en Python (auditable, testeable, reproducible por hash de entrada) + agente LLM que sintetiza sobre el contexto profesional del usuario, con grounding obligatorio contra hechos verificables.
- **Coherencia como disciplina de ingeniería**: los componentes críticos llevan un manifiesto que declara sus invariantes **y el porqué de cada una**, más las alternativas descartadas — un test en integración continua falla citando la razón, no solo la regla. La carta de voz es fuente única de verdad, verificada por tests. Prompts versionados con regresión de evaluaciones antes de cada cambio sustantivo.
- **Operabilidad**: observabilidad por llamada al modelo (prompt, contexto, costo, latencia), clasificador de intención y moderación como primera capa de defensa, OWASP Top 10 for LLMs contemplado en cada feature.
- **Stack**: Django 6 · Python 3.14 · Next.js 16 · React 19 · TypeScript · Semantic Kernel · Azure OpenAI · Supabase · pgvector

<!-- ESPACIO IMAGEN 1: arquitectura o una vista del producto -->

---

### Consultoría e implementación de IA en instituciones

Acompaño a instituciones a pasar de la curiosidad sobre IA a procesos que funcionan y que alguien adentro puede sostener.

Diseñé y entregué dos jornadas de capacitación a la plana directiva del **Centro Cultural Gabriela Mistral** (julio 2026): fundamentos de inteligencia artificial, ingeniería de prompts, el ecosistema Claude, Claude Cowork y Claude Code.

El objetivo no era enseñar una herramienta: era el **cambio de mentalidad operativa**. Que el superpoder sea la forma de usar la inteligencia artificial —ingeniería de contexto y construcción documentada de los propios procesos— y no el modelo del mes. Un equipo que trabaja así queda agnóstico a la herramienta: cuando cambia el modelo, no hay que volver a capacitar.

Con demos construidas sobre documentos reales de la institución:

- **Procesador de documentos institucionales** — toma un lote heterogéneo (PDF, imágenes escaneadas, propuestas, cotizaciones) y lo contrasta contra las bases de una convocatoria, o contra cualquier conjunto de reglas, devolviendo extracción estructurada y síntesis ejecutiva.
- **Framework operativo del contexto institucional** — persiste el contexto de cada área para poder levantarlo y automatizar procesos encima, en vez de reexplicarlo cada vez.

---

### RAIOS — marketplace de arte y artesanía chilena

Conecta artistas emergentes y artesanos con compradores, y abre una vía de monetización real para quienes están fuera del circuito comercial tradicional. Plataforma construida y funcional, con demo público; el lanzamiento se pospuso y hoy avanza a ritmo lento y deliberado. El catálogo es de demostración.

- **Backend dual razonado**: Supabase para CRUD, RLS, autenticación, almacenamiento y edge functions; Express.js propio para la lógica transaccional crítica con MercadoPago (carritos, órdenes, conciliación). Cada decisión orientada a integridad transaccional.
- **Ingeniería de producto con agentes**: orquesté el desarrollo de la lógica compleja con agentes bajo un enfoque de ingeniería de contexto, actuando como revisor crítico para acelerar ciclos sin perder calidad.
- **Calidad**: observabilidad con Winston, Jest + Supertest en backend, Vitest en frontend, documentación OpenAPI, integración y despliegue continuos en Azure vía GitHub Actions.
- **Stack**: React · Redux · TailwindCSS · Vite · Express.js · Supabase · PostgreSQL · Redis · Winston · Jest · Vitest · MercadoPago · Azure · GitHub Actions

<!-- ESPACIO IMAGEN 2: home del marketplace -->

---

## 🧠 Ingeniería de contexto, más allá del código

Entiendo la ingeniería de contexto como una forma general de abordar problemas: **estructurar el contexto de un sistema —técnico, operacional, personal— de forma que las soluciones emerjan con claridad.**

Trabajo con agentes de IA, principalmente Claude Code, no solo para escribir código: también para aterrizar ideas, diagnosticar y planificar. Sobre Claude Code armé mi propio protocolo de trabajo: fases obligatorias, estado durable entre sesiones, y una regla — **no cierro una versión cuando los tests pasan; los tests verdes son cuando empieza la auditoría**, hecha con agentes a los que se les pide encontrar fallas y no validar el trabajo. Así aparecieron errores críticos que la suite daba por buenos.

Porque con IA el cuello de botella dejó de ser escribir código: es que el sistema **conserve las decisiones que lo originaron**. Y no solo el código driftea — driftea la narrativa: los prompts, los textos de la interfaz y la voz del producto se van desalineando entre sí, y mientras más fuerte es la narrativa, más hay que sostener. Es AI slop en su versión narrativa, y se ataca igual que un bug: haciéndolo detectable.

Fuera del software: rediseñando el sistema de riego de una parcela familiar — levantar el contexto completo (infraestructura, distribución de los árboles, equipamiento) para reconstruirlo modular, sectorizado y escalable. Mismo método.

---

## 🛠️ Stack

**IA**: Semantic Kernel · Azure OpenAI · RAG · pgvector · MCP · ingeniería de prompts y de contexto

**Backend**: Python · Django · Node.js · Express · NestJS · TypeScript · REST · OpenAPI

**Frontend**: Next.js · React · TypeScript · Tailwind CSS · Redux · Vite

**Datos**: PostgreSQL · Supabase · pgvector · Redis

**Infraestructura**: Azure · GitHub Actions · Docker

**Herramientas**: Claude Code · Vitest · Jest · pytest · Winston

---

## 📝 Sobre los repositorios privados

Vista Tempesta y RAIOS están en repositorios privados: son productos en proceso de monetización. El gráfico de contribuciones refleja la actividad continua desarrollándolos.

**Acceso de solo lectura disponible a petición** para colaboraciones puntuales o demostración técnica.

---

## 📬 Contacto

- **angelo@vistatempesta.com**
- LinkedIn: [angelobuguenobug-dev](https://www.linkedin.com/in/angelobuguenobug-dev/)
- Santiago, Chile

---

*Καιρός — no el tiempo que pasa, sino el que importa.*


---
