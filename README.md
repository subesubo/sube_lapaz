# Transporte público La Paz / El Alto — mapa y planificador

Mapa interactivo y planificador de viajes del transporte público de La Paz y El
Alto: minibuses, micros, trufis, carrys, buses, **PumaKatari** y **Mi Teleférico**.
Todo funciona en el navegador (no requiere servidor).

**Ver en vivo:** https://subesubo.github.io/  ← (edita esta línea cuando publiques)

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

## Publicar en GitHub Pages

1. En la organización **subesubo**, crea un repositorio público llamado
   **`subesubo.github.io`** (ese nombre exacto da la URL más limpia).
2. Sube `index.html` (y este `README.md`).
3. **Settings → Pages → Source:** rama `main`, carpeta `/ (root)` → **Save**.
4. En ~1 minuto estará en **`https://subesubo.github.io/`**.

Para actualizar: sube un nuevo `index.html`.

## Datos y créditos

- Mapa base © OpenStreetMap contributors. Búsqueda: Nominatim.
- Rutas del transporte tradicional: **GAMLP** — red autorizada/registrada,
  extraída de la app municipal «Moviéndonos por La Paz» (instantánea ~2021).
- PumaKatari: servicio `simon.lapaz.bo` (datos vigentes).

## Aviso

Proyecto **no oficial**. La red autorizada puede no coincidir con la operación
real actual. Las rutas informales (minibús/micro/trufi/carry) no tienen paradas
fijas ni horarios; los tiempos son estimaciones, no horarios reales.

---

*Interactive public-transit map & trip planner for La Paz / El Alto, Bolivia.
Single self-contained HTML file — no backend. Unofficial project.*
