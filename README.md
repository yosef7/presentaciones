# Mis Presentaciones con Slidev

Repositorio publico para organizar, versionar y compartir presentaciones creadas con [Slidev](https://sli.dev/).

## Presentaciones disponibles

Cada carpeta del repositorio corresponde a una presentacion independiente. Entra a la carpeta de una presentacion para ver su README, contenido, comandos y referencias propias.

## Estructura

Cada presentacion mantiene sus dependencias, configuracion y archivo principal `slides.md` dentro de su propia carpeta.

```text
presentaciones/
├── nombre_de_la_presentacion/
│   ├── slides.md
│   ├── package.json
│   ├── pnpm-lock.yaml
│   └── README.md
└── README.md
```

## Requisitos

- Node.js 20.19 o superior
- pnpm 10 o superior

## Como usar

1. Clona el repositorio:

   ```bash
   git clone https://github.com/yosef7/presentaciones.git
   cd presentaciones
   ```

2. Entra a la carpeta de la presentacion que quieres ejecutar:

   ```bash
   cd nombre_de_la_presentacion
   ```

3. Instala dependencias y levanta Slidev:

   ```bash
   pnpm install
   pnpm run dev
   ```

4. Abre la URL local que muestra Slidev, normalmente <http://localhost:3030>.

## Comandos utiles

Desde la carpeta de cada presentacion:

| Comando | Uso |
| --- | --- |
| `pnpm run dev` | Ejecuta la presentacion en modo desarrollo |
| `pnpm run build` | Genera la version estatica en `dist/` |
| `pnpm run export` | Exporta la presentacion con las opciones de Slidev |

## Recomendacion para GitHub

Para completar la ficha del repositorio en GitHub:

- Description: `Presentaciones tecnicas y ejecutivas creadas con Slidev.`
- Topics: `slidev`, `presentaciones`, `ia`, `typescript`, `vue`, `educacion`
- Website: agrega aqui la URL publica cuando publiques una presentacion con Vercel, Netlify o GitHub Pages.

## Autor

Jose Arnulfo R. H.  
GitHub: [@yosef7](https://github.com/yosef7)
