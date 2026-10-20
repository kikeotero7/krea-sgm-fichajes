# SGM Fichajes · Control de obra

App de control de obra y fichajes para **SGM Construcciones · Trabajos Integrales**, creada por **KREA Digital Studio**.

Publicada en https://sgm-fichajes.kreadigitalstudio.es (GitHub Pages, rama `main`, carpeta raíz; DNS en OVH: CNAME `sgm-fichajes` → `kikeotero7.github.io.`).

La app de presupuestos y facturas de SGM está en el repositorio `krea-sgm` (https://sgm.kreadigitalstudio.es).

## Qué hace

- **Fichar:** PIN de 4 dígitos, comprobación de zona GPS y de horario, motivo de incidencia, justificante, corrección de fichajes y modo tablet de obra.
- **Gestión (Sergio):** resumen en directo, obras con zona en el mapa, equipo, historial con exportación CSV, asistencia mensual, incidencias y ajustes (horarios de verano e invierno, festivos, avisos y copias cifradas).

## Demo

PIN de prueba: Miguel 1234 · David 2345 · Antonio 3456. Los datos de ejemplo se renuevan cada día y las pruebas se guardan solo en el navegador de cada persona.

## Archivos

- `index.html`, `manifest.webmanifest`, iconos y `logo.webp`: la app que se publica.
- `app.src.html`: código fuente. Después de editarlo, ejecuta `python3 build.py` para regenerar `index.html` (y `preview.html`, la versión con el logo incrustado).
- `portafolio/`: ficha del proyecto y capturas para enseñar a clientes.
