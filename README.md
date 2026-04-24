# Angelo Paolo Bugueño

**Founder & AI Engineer** · Santiago, Chile

Construyo productos digitales donde IA, ingeniería de producto y visión de negocio se cruzan. Heavy user de Claude Code con workflow AI-native en producción. Formación Full Stack reciente (Talento Digital SENCE, abr 2026) + preparando examen Azure AI Engineer Associate (AI-102).

> *"El contexto bien estructurado es la forma más alta de ingeniería."*

---

## 🔭 Proyectos actuales

### ELIOX / Kairos Engine — AI Career Companion para LATAM

Plataforma que ayuda a profesionales tech a redescubrir su identidad profesional y encontrar oportunidades alineadas con quienes son.

- **Arquitectura**: híbrida Python + Semantic Kernel + Azure OpenAI. Scoring engine determinista (auditable, testeable) + agente LLM con RAG sobre pgvector.
- **Pipeline de síntesis**: 6 plugins Semantic Kernel orquestados en 7 fases (CultureRadar, RequirementClassifier, SASEvaluator, ContentDrafting, Verification, BrandCoherence).
- **Calidad**: 900+ tests automatizados. Observability por LLM call (prompt, contexto, costo, latencia persistidos). Guardrails activos (intent classifier + Azure Content Safety). OWASP Top 10 for LLMs awareness por feature.
- **Principio core**: *"el LLM clasifica, el código calcula"* — lógica determinista en Python, el LLM para síntesis/clasificación. Patrón Recover → Synthesize → Validate → Persist garantizando grounding contra corpus del usuario.
- **Stack**: Django 6 · Python 3.14 · Next.js 16 · React 19 · TypeScript · Semantic Kernel · Azure OpenAI · Supabase · pgvector

*Demo no pública por el momento (infraestructura LLM con costo por uso). Acceso coordinado disponible para procesos de selección.*

<!-- ESPACIO IMAGEN 1: Screenshot de arquitectura o UI de Kairos
Insertar aquí:
![Kairos architecture](URL_DE_LA_IMAGEN)
-->

---

### RAIOS — Marketplace de Arte y Artesanía Chilena

E-commerce que conecta artistas emergentes y artesanos con compradores. Democratiza el acceso a arte y abre vía de monetización real.

- **Demo pública**: [delightful-island-08498ff0f.6.azurestaticapps.net](https://delightful-island-08498ff0f.6.azurestaticapps.net/)
- **Arquitectura**: backend dual — Supabase (CRUD, RLS, storage, auth, edge functions) + Express.js custom para lógica transaccional crítica con MercadoPago (carritos, órdenes, conciliación).
- **Calidad**: observability con Winston, suites Jest + Supertest (backend) + Vitest (frontend), documentación OpenAPI/Swagger, CI/CD automatizado en Azure vía GitHub Actions.
- **Lanzamiento oficial**: 14 de mayo 2026.
- **Stack**: React · Redux · TailwindCSS · Vite · Express.js · Supabase · PostgreSQL · Winston · Jest · Vitest · MercadoPago · Azure · GitHub Actions

<!-- ESPACIO IMAGEN 2: Screenshot de RAIOS (landing o vista producto)
Insertar aquí:
![RAIOS marketplace](URL_DE_LA_IMAGEN)
-->

---

## 🧠 Enfoque: Context Engineering como filosofía

Más allá del patrón de desarrollo agéntico, entiendo *context engineering* como una forma general de abordar problemas complejos: **estructurar el contexto de un sistema (técnico, operacional, personal) de forma que las soluciones emerjan con claridad**.

Eso atraviesa lo que construyo:

- **Kairos**: cada plugin Semantic Kernel recibe contexto estructurado del corpus profesional del usuario. La calidad del output correlaciona directamente con la calidad del contexto, no con el prompt.
- **RAIOS**: separación consciente entre contexto transaccional (Express.js custom) y contexto CRUD (Supabase) según integridad requerida.
- **Proyectos no-software**: actualmente rediseñando un sistema de riego artesanal en parcela familiar — levantando el contexto completo (infraestructura, elementos, distribución de árboles, equipamiento) para reconstruir modular, sectorizado y escalable.

El context engineering aplicado más allá del código es una forma de resolver problemas que se puede entrenar. Es mi apuesta metodológica más fuerte.

---

## 🛠️ Stack principal

**AI / ML**: Semantic Kernel · Azure OpenAI · RAG · pgvector · LLMOps · MCP · prompt engineering

**Backend**: Python · Django · Node.js · Express · NestJS · TypeScript · REST · OpenAPI

**Frontend**: Next.js · React · TypeScript · Tailwind CSS · Redux · Vite

**Data**: PostgreSQL · Supabase · pgvector

**DevOps**: Azure · GitHub Actions · Docker · Azure DevOps

**Tooling**: Claude Code (heavy user, workflow AI-native desde meses) · Vitest · Jest · Pytest · Winston

---

## 📝 Sobre repositorios privados

Kairos Engine y RAIOS están en repositorios privados por tratarse de proyectos en proceso de monetización. El contribution graph refleja la actividad continua desarrollándolos.

**Acceso de solo-lectura disponible a petición** para procesos de selección, colaboraciones puntuales o demostración técnica.

---

## 📬 Contacto

- LinkedIn: https://www.linkedin.com/in/angelobuguenobug-dev/
- Email: angelopaolo0223@gmail.com
- Santiago, Chile · Abierto a roles AI Engineer / FDE / Founding Engineer / Product Engineer (remote o híbrido)

---

*Καιρός — no el tiempo que pasa, sino el que importa.*
```

---
