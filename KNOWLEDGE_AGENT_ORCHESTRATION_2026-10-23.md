# Hivia — Conocimiento federado para contratación de equipos de IA

Fuente canónica: https://github.com/CloudCo-Organization/CloudCo-Core/blob/main/docs/knowledge/university/SECRETSAUCE_CAMUNDA_TRANSFERABLE_AGENT_ORCHESTRATION_LESSONS_2026-10-23.md

Hivia es la app para contratar equipos de agentes IA (README canónico). Reutiliza los 16 agentes de CloudCo según organización, plan, capacidades y permisos; no duplica un motor de agentes.

**Lecciones incorporadas**: de SecretSauce, contexto de marca reutilizable y Skill workflows; de Camunda, procesos durables y agentes especializados con estado, reintentos y QA auditado. No instalar esos terceros.

**Arquitectura**: Cloudflare ejecuta; GitHub versiona; THE CORE aporta AI Engine y capacidades; Supabase solo puente/fallback justificado. Protección multi-tenant; sin Higgsfield, sin gasto incremental no autorizado.

**Estado**: documento de conocimiento, no ejecución de un agente ni implementación del gateway de Hivia. La certificación E2E por agente sigue pendiente.
