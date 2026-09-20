# Colección de prototipos comerciales POS + Web

Esta carpeta contiene **6 proyectos independientes** más un `index.html` raíz que funciona como selector comercial.

## Estructura

- `prototipos_pos/pos_basico`
- `prototipos_pos/pos_estandar`
- `prototipos_pos/pos_plus`
- `prototipos_web/web_informativa`
- `prototipos_web/web_ventas`
- `prototipos_web/web_plus`

Cada proyecto contiene su propio `index.html`, `styles.css`, `app.js`, `manifest.json`, `sw.js`, iconos PWA y `README.md`. No comparte código en tiempo de ejecución con los demás.

## Uso rápido en una visita comercial

La forma más cómoda es abrir la carpeta raíz con un servidor local:

```bash
python -m http.server 8080
```

Después abre `http://localhost:8080` y usa el selector para entrar al plan deseado.

También puedes abrir directamente el `index.html` de cada proyecto. En ese modo funcionan las demostraciones y `localStorage`; para instalación PWA y service worker conviene usar `localhost`.

## Datos

Todos los datos son ficticios y se guardan únicamente en el `localStorage` del navegador. No existe backend, VPS ni base de datos externa.

## Tecnología de esta versión

HTML5, CSS3 y JavaScript moderno sin dependencias externas. La decisión de no incluir un proceso de compilación permite transportar la colección en USB y ejecutarla rápidamente en PC, monitor touch, tablet o celular. La estructura está separada por componentes de interfaz y puede migrarse a React cuando el producto pase de prototipo comercial a implementación real.
