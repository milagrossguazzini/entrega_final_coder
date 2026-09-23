# Ecosistema de IA Autónomo — Planificador de Contenido Tuttilandia

Proyecto final del curso IA Automation (CoderHouse). Sistema de automatización que 
toma una idea de contenido cargada en Airtable, la redacta con IA respetando el tono 
de marca real de Tuttilandia, y espera aprobación humana antes de marcarla como lista 
para publicar.

## Workflow
- **Orquestador:** n8n
- **Base de datos:** Airtable (3 tablas relacionadas — Ideas_Contenido, Piezas_Generadas, Manual_de_Marca)
- **IA:** OpenAI gpt-5-mini vía AI Agent con RAG (Airtable Tool)
- **Canal de salida / HITL:** Gmail (Send and Wait for Response)

## Contenido del repositorio
- `documentación_entrega_final.pdf` — diagrama de arquitectura, esquema de datos, matriz de costos, 
  seguridad y resiliencia
- `workflow.json` — blueprint exportado del flujo de n8n
- `screenshots/` — evidencia de ejecución (canvas de n8n, vistas de Airtable, mails)
    - `ejecución_workflow_sguazzini.mp4` — video de la ejecución completa del flujo
- Link al dashboard público (Airtable Shared View) y a la base en modo lectura: 
  incluidos en el PDF

## Caso de uso real
Aplicado al negocio real de Tuttilandia (marroquinería, Santa Fe, Argentina) — 
planificación de contenido para Instagram, WhatsApp comunidad y email marketing.
