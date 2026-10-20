# Juan Martínez Jiménez

Co-fundador y CTO de [FormasDigital](https://formasdigital.com) · Murcia, España

Diseño y construyo automatizaciones, agentes de IA y sistemas web para empresas.
Me interesa la IA que funciona en producción y se puede medir, no la demo.

## Qué hago

- **Automatización e IA:** agentes conversacionales para WhatsApp, extracción de documentos con LLM, integraciones con n8n.
- **Web y producto:** webs con Astro y Next.js, CRMs a medida con PostgreSQL.
- **Datos:** modelado y lógica de negocio en PostgreSQL y SQL.

## Cómo trabajo

**Entender → Analizar → Diseñar → Implementar → Medir.**
Primero el proceso de negocio y después la tecnología. La IA solo entra cuando aporta más que una regla simple.

## Stack

TypeScript · Python · PostgreSQL · Docker · n8n · Astro · Next.js · GitHub Actions

## Proyectos

| Proyecto | Qué es |
| --- | --- |
| [agent-evals](https://github.com/juanmartinezjimenez/agent-evals) · [v0.4.0](https://github.com/juanmartinezjimenez/agent-evals/releases/tag/v0.4.0) | Evaluación de agentes LLM con casos de prueba en YAML, también conversaciones de varios turnos: puntúa cada respuesta, explica los fallos y compara dos ejecuciones caso a caso para detectar regresiones. Incluye una GitHub Action que comenta el resultado en cada PR y detecta grabaciones desactualizadas. Python, Pydantic, uv, GitHub Actions |
| [mcp-workspace](https://github.com/juanmartinezjimenez/mcp-workspace) · [v0.1.0](https://github.com/juanmartinezjimenez/mcp-workspace/releases/tag/v0.1.0) | Servidor MCP que da a un agente acceso a una carpeta de notas Markdown y una lista de tareas: solo lectura por defecto, cada escritura se habilita por su nombre y un sandbox de rutas impide salir de la carpeta, también en Windows. Probado en Linux y Windows con un cliente MCP real. TypeScript, MCP SDK, Zod, Vitest |
| [delivery-playbook](https://github.com/juanmartinezjimenez/delivery-playbook) | Mi metodología de trabajo: cinco fases, plantillas de diagnóstico, propuesta y traspaso, y checklists para poner en producción sistemas con IA |
| [repo-template](https://github.com/juanmartinezjimenez/repo-template) | Plantilla base de todos mis proyectos: CI, control de secretos con gitleaks, ADRs y convenciones |

Iré añadiendo proyectos propios y casos de estudio de trabajos reales, siempre sin código ni datos de clientes.
