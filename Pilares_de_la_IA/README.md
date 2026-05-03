# Los 5 Pilares de la IA

Presentacion ejecutiva creada con [Slidev](https://sli.dev/) para directivos, project managers, auditores de sistemas y lideres de TI.

## Objetivo

Explicar cinco conceptos fundamentales de IA con enfoque de liderazgo, riesgo operativo y toma de decisiones:

- Tokens
- Context window
- Temperature
- Hallucination
- RAG, o Retrieval-Augmented Generation

## Requisitos

- Node.js 20.19 o superior
- pnpm 10 o superior

## Ejecutar localmente

```bash
pnpm install
pnpm run dev
```

Luego abre la URL local que indique Slidev, normalmente <http://localhost:3030>.

## Editar contenido

El contenido principal vive en [slides.md](./slides.md). Slidev recarga los cambios automaticamente mientras `pnpm run dev` esta activo.

## Comandos

| Comando | Descripcion |
| --- | --- |
| `pnpm run dev` | Ejecuta la presentacion en modo desarrollo |
| `pnpm run build` | Genera la version estatica en `dist/` |
| `pnpm run export` | Exporta la presentacion usando Slidev |

## Despliegue

La carpeta incluye configuracion base para:

- [Vercel](./vercel.json)
- [Netlify](./netlify.toml)

## Referencias

- Gartner. [Gartner Hype Cycle Identifies Top AI Innovations in 2025](https://www.gartner.com/en/newsroom/press-releases/2025-08-05-gartner-hype-cycle-identifies-top-ai-innovations-in-2025). Gartner Newsroom, 5 de agosto de 2025.
- ISO. [ISO/IEC 42001:2023 - AI management systems](https://www.iso.org/standard/42001). Estandar internacional para establecer, implementar, mantener y mejorar un sistema de gestion de IA.
- NIST. [Artificial Intelligence Risk Management Framework (AI RMF 1.0)](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10). Marco voluntario para gestionar riesgos y promover IA confiable y responsable.
