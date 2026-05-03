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
