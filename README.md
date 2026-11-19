# Checkpoint 1 - Agente de leads RARA MATERIA (n8n)

Flujo: Chat Trigger → AI Agent (Tools Agent, máx. 6 iteraciones) → Gmail.

Modelo: Groq gpt-oss-120b. Tool: Google Sheets `registrar_lead`.

Pruebas: con datos completos usa la tool; con pregunta general no.

Importar: n8n → Import from file → checkpoint1_nombre_apellido.json
