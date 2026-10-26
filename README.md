# Catálogo de productos con Astro y una API

Sitio de ejemplo creado para el laboratorio: consume productos desde DummyJSON, presenta las tarjetas mediante un componente reutilizable y permite filtrar por nombre.

## API utilizada
`https://dummyjson.com/products?limit=12`

## Requisitos
- Node.js 18 o superior
- npm
- Conexión a internet para consultar la API y cargar las imágenes

## Ejecutar
```bash
npm install
npm run dev
```
Abre la dirección local que indique Astro, normalmente `http://localhost:4321`.

## Comprobar la compilación
```bash
npm run build
```

## Estructura
- `src/layouts/Layout.astro`: estructura HTML común.
- `src/components/ProductoCard.astro`: tarjeta reutilizable que recibe datos mediante props.
- `src/pages/index.astro`: consulta la API, recorre los productos con `map()` y contiene el buscador.
- `src/styles/global.css`: estilos responsivos.
# catalogo-con-api
