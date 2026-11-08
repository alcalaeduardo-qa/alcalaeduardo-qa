# Hola, soy Eduardo Alcalá 👋

**AI Agent QA & LLM Evaluation** · Python · Pytest · Playwright · REST APIs · LLM Evals · Red Teaming

[![LinkedIn](https://img.shields.io/badge/LinkedIn-eduardo--alcala--qa-0a66c2?style=flat&logo=linkedin)](https://linkedin.com/in/eduardo-alcala-qa)
[![Portfolio](https://img.shields.io/badge/Portfolio-alcalaeduardo--qa.github.io-7c3aed?style=flat&logo=github)](https://alcalaeduardo-qa.github.io)
[![Ubicación](https://img.shields.io/badge/Ubicaci%C3%B3n-Zacatecas%2C%20M%C3%A9xico-00e5ff?style=flat)](https://alcalaeduardo-qa.github.io)
[![Disponible](https://img.shields.io/badge/Disponible-Remoto%20LATAM-4ade80?style=flat)](https://linkedin.com/in/eduardo-alcala-qa)

---

## Lo que hago

Mido si los agentes de IA realmente funcionan, y los hago fallar antes de que fallen con tus usuarios.

7 años de ingeniería de calidad en manufactura industrial, ahora aplicados al software y a los sistemas con LLMs. Diseño evals, ataques de red-teaming y guardrails con la misma mentalidad de cero defectos: cada falla posible tiene un control y una métrica que la detecta antes de producción.

---

## Proyectos destacados

### 1. Evaluación de un agente de ventas con LLM

> Mido un agente real con datos reales

Evalué 3,591 respuestas de un agente de ventas con LLM contra 1,103 conversaciones reales, a lo largo de 116 días de operación con humano en el circuito.

| Métrica | Valor |
|---|---|
| Respuestas evaluadas | 3,591 |
| Conversaciones etiquetadas | 1,103 |
| Adherencia al spec por versión del prompt | **38.4 % → 91.6 %** |
| Mayor caída del embudo | Precio a pago, 51.7 % |
| Modos de falla clasificados | 9 (FM0 a FM8) |

**Hallazgo clave:** el 15 % de leads sin respuesta venía del transporte manual, no del modelo. Ese hallazgo llevó al siguiente proyecto.

**Stack:** Python · Pytest · GitHub Actions

[Ver repositorio →](https://github.com/alcalaeduardo-qa/llm-sales-agent-eval)

### 2. Sofía · Agente de ventas con IA en producción

> Construyo el agente automático, medido desde el primer día

Agente de WhatsApp con Claude que atiende clientes reales. La seguridad no depende del prompt: crisis, precios, pagos e inyecciones se controlan en código, y un humano aprueba cada pago desde Telegram.

| Métrica | Valor |
|---|---|
| Casos de evaluación (DeepEval) | 69, con LLM como juez |
| Casos que pasan | **32.8 % → 94 %** |
| Red-teaming | 21 / 21 ataques bloqueados |
| Clasificador de crisis | 27/27 sensibilidad · 72/72 especificidad |
| Tests automatizados | 562 · 97 % de cobertura |
| FMEA de IA | 24 modos de falla |
| Auditoría de seguridad | 22 pistas revisadas |

**Lo que demuestra:** CI que bloquea cada cambio si los evals bajan del 85 %, defensa contra inyección de prompts, detección de filtración del prompt, humano en el circuito, topes de gasto y retención de datos de 90 días.

**Stack:** Python · FastAPI · Claude API · DeepEval · Supabase · Docker · GitHub Actions · Railway

[Ver repositorio →](https://github.com/alcalaeduardo-qa/llm-whatsapp-sales-agent)

---

## Otros proyectos de QA

| Proyecto | Descripción | Stack |
|---|---|---|
| [Urban Scooter](https://github.com/alcalaeduardo-qa/urban-scooter-qa) | Framework QA completo: 251 casos, 81 bugs, web, API, móvil y base de datos | Python · Playwright · Appium · PostgreSQL · Jira REST API |
| [Urban Routes E2E](https://github.com/alcalaeduardo-qa/qa-project-Urban-Routes-es) | Framework Selenium con POM · 9/9 tests | Python · Selenium · CDP · Pytest |
| [Urban Grocers API](https://github.com/alcalaeduardo-qa/qa-project-Urban-Grocers-app-es) | Automatización de API REST con BVA · 9 casos | Python · Pytest · requests |

---

## Stack técnico

```
IA y evals      →  Claude API · DeepEval · LLM como juez · Red-teaming · Guardrails · Tool use
Testing         →  QA manual · Black-box · BVA · E2E · Regresión · Móvil
Automatización  →  Python · Pytest · Selenium · Playwright · Appium · POM
API             →  Postman · requests · REST APIs · FastAPI · Webhooks
Base de datos   →  SQL · PostgreSQL · Supabase · Validación de integridad
DevOps          →  Docker · GitHub Actions · Railway · Linux · Bash
Gestión         →  Jira · Jira REST API · Git · GitHub · Agile · Scrum
```

---

## Background industrial aplicado a QA e IA

Antes del software, 7 años como Líder Técnico de Prueba Eléctrica en Kauffman Engineering, en manufactura de arneses para los sectores náutico y de maquinaria de jardín.

| Metodología industrial | Aplicación en QA de software e IA |
|---|---|
| FMEA | Risk-based testing y FMEA de IA (24 modos de falla en Sofía) |
| RCA | Investigación metodológica de bugs y de fallas del modelo |
| Kaizen | Mejora continua de suites y de prompts, medida con evals |
| APQP | Planeación estructurada de pruebas |
| Trazabilidad | Matriz de trazabilidad y versionado de prompts |

La manufactura cero defectos y la evaluación de IA son la misma filosofía. Solo cambian los dominios.

---

## Contacto

Disponible para roles de **AI Agent QA**, **LLM Evaluation** y **QA Automation**. Remoto LATAM. Disponibilidad inmediata.

[LinkedIn](https://linkedin.com/in/eduardo-alcala-qa) · [Portfolio](https://alcalaeduardo-qa.github.io) · [Email](mailto:alcala.edugar@gmail.com)
