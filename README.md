# Fundación ABAnzando — Landing page

Sitio estático de la Fundación ABAnzando (fundacionabanzando.org), desplegado en Cloudflare Workers (static assets).

## Estructura

```
public/
  index.html       # página principal
  fonts/           # Baloo 2 y Nunito (woff2)
  images/          # fotos de la landing
  favicon.svg
wrangler.toml       # configuración de Cloudflare Workers (assets)
```

## Desarrollo local

```bash
npm install
npm run dev
```

## Despliegue manual

```bash
npm run deploy
```

El repo también está conectado a Cloudflare Workers vía integración con GitHub, por lo que cada push a `main` dispara un despliegue automático.
