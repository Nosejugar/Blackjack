# Blackjack

Mesa de Blackjack como PWA: se instala como ícono en el teléfono y funciona sin conexión.

**Jugar:** https://nosejugar.github.io/blackjack/

## Reglas
- Zapato de 6 mazos, se baraja cuando quedan menos de 75 cartas.
- Blackjack paga 3 a 2. El crupier se planta en todo 17.
- Doblar con dos cartas; dividir una vez (ases divididos reciben una sola carta).
- Banca inicial de $1,000, guardada en el navegador.

## Instalar
- **iPhone (Safari):** Compartir → *Agregar a inicio*.
- **Android (Chrome):** menú ⋮ → *Instalar app*.

## Archivos
- `index.html` — el juego completo (HTML, CSS y JS en un archivo).
- `manifest.webmanifest`, `sw.js`, `*.png` — lo que lo hace instalable y offline.
- `.github/workflows/pages.yml` — publica en GitHub Pages en cada push a `main`.

Al cambiar `index.html`, sube también `CACHE` en `sw.js` (`blackjack-v2`, …) para que los teléfonos tomen la versión nueva.
