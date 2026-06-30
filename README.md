# SDLC en la Era de la Inteligencia Artificial

Presentación interactiva dirigida a Tech Leads y desarrolladores. Explica cómo **IBM Bob** (asistente de IA) se integra en cada etapa del ciclo de vida del desarrollo de software (SDLC).

## Propósito

Mostrar a los equipos de desarrollo cómo aprovechar IBM Bob 2.0 como herramienta de productividad a lo largo de todo el SDLC — desde la planificación hasta el mantenimiento — cubriendo sus capacidades, modos de operación, herramientas y opciones de personalización.

## Contenido de la Presentación

| Diapositiva | Tema |
|-------------|------|
| 1 | Título — SDLC en la era de la IA |
| 2 | ¿Qué es Bob? — roles y capacidades |
| 3 | ¿Qué es un Agente? — diferencia entre LLM y agente |
| 4 | Herramientas (Tools) — Read, Write, Command, Mode, Question, MCP |
| 5 | Bob en cada etapa del SDLC |
| 6 | Modos de Operación — Agent, Plan, Ask y Modos Personalizados |
| 7 | Skills Personalizadas |
| 8 | MCP: Protocolo de Contexto del Modelo |
| 9 | Ingeniería de Prompts |
| 10 | Personalización Avanzada — `~/.bob/rules/`, `settings/`, `skills/` |
| 11 | Recursos y Artículos |
| 12 | Conclusión y Puntos Clave |

## Estructura del Proyecto

```
./
├── presentacion.html   # Presentación principal (self-contained)
├── images/             # Imágenes y códigos QR usados en las diapositivas
│   ├── Bob_web_page.png
│   ├── Agent_Sensores_Actuadores.png
│   ├── qr-code-Bob_doc.png
│   ├── medium_ibm_bob_mcps.png
│   └── medium_ibm_bob_mode_skills.png
└── README.md
```

## Cómo Usar

1. Abre `presentacion.html` directamente en cualquier navegador moderno — no requiere servidor ni dependencias externas.
2. Navega con los botones **Anterior / Siguiente** o con las teclas `←` / `→`.
3. Activa el **Modo Oscuro** con el botón en la esquina superior derecha.

## Temas Clave Cubiertos

- **Qué es IBM Bob** — asistente de IA basado en LLM con roles de Asistente Inteligente, Desarrollador, Arquitecto de Soluciones y Gestor de Proyectos.
- **Agentes vs Sistemas** — distinción entre un LLM, un agente y un sistema multi-agente.
- **Herramientas de Bob** — capacidades de lectura, escritura, ejecución de comandos e integración vía MCP.
- **SDLC completo** — cómo Bob apoya Planificación, Diseño, Desarrollo, Pruebas, Despliegue y Mantenimiento.
- **Modos de Operación** — Agent (acción), Plan (estrategia), Ask (consulta) y modos personalizados.
- **Skills Personalizadas** — flujos de trabajo determinísticos y reutilizables.
- **MCP (Model Context Protocol)** — protocolo para conectar Bob con APIs, bases de datos y servicios externos.
- **Ingeniería de Prompts** — mejores prácticas para obtener resultados efectivos.
- **Personalización Avanzada** — uso de `~/.bob/rules/`, `~/.bob/settings/` y `~/.bob/skills/`.

## Audiencia

Tech Leads, desarrolladores senior y equipos de software interesados en adoptar herramientas de IA en su flujo de trabajo diario.

## Recursos Adicionales

- 📖 [Documentación IBM Bob](https://bob.ibm.com/docs/ide)
- 📝 IBM Bob–Driven MCP in Practice: Concepts, Use Cases, and Building a Java Quarkus MCP Server
- 🎯 IBM Bob Modes vs Skills: The Complete Guide to Reliable AI-Assisted Development
