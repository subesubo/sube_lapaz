# Transporte público La Paz / El Alto — mapa y planificador

Mapa interactivo y planificador de viajes del transporte público de La Paz y El
Alto: minibuses, micros, trufis, carrys, buses, **PumaKatari** y **Mi Teleférico**.
Todo funciona en el navegador (no requiere servidor).

**Ver en vivo:** https://subesubo.github.io/sube_lapaz/

## Qué incluye

- **Explorar rutas:** 979 rutas / 613 líneas, filtrables por tipo de transporte y
  operador, con búsqueda por línea o destino. Clic en una ruta para ver operador,
  tarifa, horario y recorrido calle por calle.
- **Planificar viaje:** origen → destino con búsqueda de direcciones o tocando el
  mapa. Calcula qué líneas tomar, dónde transbordar y los tramos a pie,
  respetando el **sentido de circulación** (ida/vuelta). Estima tiempo, distancia
  y tarifa. Preferencia por tipo de transporte, ubicación GPS, marcadores
  arrastrables y enlace compartible.
- **Móvil:** panel inferior deslizable, pensado para usarse en el teléfono.

## Actualizar el sitio

El sitio se publica con **GitHub Pages** desde este repositorio
(`subesubo/sube_lapaz`, rama `main`, carpeta raíz). Para publicar un cambio,
reemplaza `index.html` y súbelo:

    git add index.html
    git commit -m "actualiza el mapa"
    git push

En ~1–3 minutos el cambio queda en vivo.

> ¿Dominio propio? Puedes agregar uno (p. ej. `sube.bo`) en
> **Settings → Pages → Custom domain** y apuntar el DNS a GitHub.

## Datos y créditos

- Mapa base © OpenStreetMap contributors. Búsqueda de direcciones: Nominatim.
- Rutas del transporte tradicional: **GAMLP** — red autorizada/registrada,
  extraída de la app municipal «Moviéndonos por La Paz» (instantánea ~2021).
- PumaKatari: servicio `simon.lapaz.bo` (datos vigentes).

## Aviso

Proyecto **no oficial**, sin relación con el GAMLP ni los operadores. La red
autorizada puede no coincidir con la operación real actual. Las rutas informales
(minibús / micro / trufi / carry) no tienen paradas fijas ni horarios; los
tiempos y tarifas son estimaciones, no información oficial.

---

*Interactive public-transit map & trip planner for La Paz / El Alto, Bolivia.
Single self-contained HTML file — no backend. Unofficial project.*
