# Owner Portal — Panel de Propietarios

Prototipo del panel de propietarios de **Costa Sol Resort** (gestionado por Bookhap).

Es una página HTML autocontenida (`index.html`), sin dependencias ni paso de build: basta con abrirla en el navegador o servirla con GitHub Pages.

## Secciones

- **Resumen** — ingreso neto estimado del mes, ocupación, próximos huéspedes e ingresos de los últimos 6 meses.
- **Calendario** — disponibilidad de la unidad; el propietario puede bloquear días para uso personal (se guarda en `localStorage`).
- **Ingresos** — desglose de bruto, comisiones OTA, fee de gestión y neto; origen de las reservas por canal.
- **Reservas** — historial y próximas estancias.
- **Facturación** — liquidación del mes y liquidaciones anteriores.

Incluye diseño responsive (sidebar en escritorio, barra inferior en móvil) y tema claro/oscuro.

> Todos los datos son de demostración.

## Uso local

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```
