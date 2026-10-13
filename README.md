# NES Player — plantilla web

Página estática de un solo jugador con JSNES, pantalla Canvas, teclado y controles táctiles.

## Configurar
1. Coloca una ROM NES autorizada en `roms/super-mario-bros.nes` para que la página la cargue automáticamente.
2. Publica el contenido de esta carpeta en un hosting estático que sirva archivos y permita `fetch` del archivo `.nes`.
3. Necesita conexión para cargar JSNES desde jsDelivr. Para alojar también el emulador localmente, descarga y sirve la versión del paquete JSNES que elijas y cambia la etiqueta `<script>`.

## Probar en local
Por las restricciones del navegador sobre `fetch` desde `file://`, se recomienda un servidor HTTP local (por ejemplo, `python -m http.server 8000`) y abrir `http://localhost:8000`. Alternativamente, el botón “Probar ROM local” permite elegir un archivo `.nes` desde el dispositivo.

## Importante
No se incluye ninguna ROM. Solo aloja o distribuye una ROM si tienes los derechos o autorización necesarios. El paquete no está afiliado a Nintendo.
