# Panel de gastos

Panel de control de gastos personales de una sola página, sin dependencias ni backend.

## Qué hace

- Registra gastos por concepto, importe, fecha y categoría.
- Organiza los gastos por mes (pestañas) y permite añadir meses futuros.
- Calcula el total del mes, la media diaria y lo que queda de presupuesto.
- Muestra el desglose por categoría y el acumulado del mes en un gráfico simple.
- Calcula un "bote de ahorro" a partir de ingresos y presupuesto de cada mes.
- Guarda todo en `localStorage` del navegador; permite descargar y restaurar una copia en JSON.

## Uso

Abre [`panel-gastos.html`](./panel-gastos.html) directamente en el navegador. No requiere instalación ni servidor.

## Datos

Los datos se guardan localmente en el navegador (no se envían a ningún servidor). Usa los botones **Descargar copia** / **Restaurar copia** para hacer una copia de seguridad o pasar los datos a otro dispositivo.
