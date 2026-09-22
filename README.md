# Firmar documento

Firma con el dedo en el teléfono y estampa la firma sobre un PDF, todo desde el navegador.

- La firma se dibuja en un canvas (pointer events: dedo, lápiz o mouse) y se recorta a PNG con fondo transparente.
- El PDF se abre, se muestra la página 1 y la firma se arrastra hasta la línea de firma.
- El PDF con la firma se genera en el propio dispositivo con pdf-lib y se descarga.
- **Nada se sube a ningún servidor**: no hay backend, no hay subida de archivos. El PDF nunca sale del teléfono.

Librerías: pdf-lib 1.17.1 y pdf.js 3.11.174 (incluidas en `vendor/`).
