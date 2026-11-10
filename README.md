# BOLEAUTO · Boletos automáticos

Aplicación web para diseñar, numerar e imprimir boletos y rifas. Funciona en computadora y celular, y se puede **instalar como app** en Android, iPhone y computadora.

## Qué hace
- Numeración automática (inicio–fin, formatos 1/32, 1 DE 32, FOLIO 001…).
- Talón opcional con campos para llenar, línea de corte y número.
- Temas, degradados, texturas, marcos, imágenes y logos.
- Acomodo automático en la hoja (carta, oficio, A4…) y exportación a PDF listo para imprimir.
- **Diseño IA**: sube un boleto hecho con cualquier IA y conviértelo en capas editables (OCR en español, sin servidor).

## Instalar como app
- **Android / Chrome / Edge**: botón **Instalar** en la barra, o menú ⋮ → *Instalar app*.
- **iPhone / iPad (Safari)**: Compartir → *Agregar a pantalla de inicio*.

## Publicación
Sitio estático publicado con Cloudflare Pages (sin paso de compilación, carpeta raíz `/`).

## Licencias de terceros
El OCR usa [tesseract.js-core](https://github.com/naptha/tesseract.js-core) y el modelo `spa` de [tessdata_fast](https://github.com/tesseract-ocr/tessdata_fast), ambos con licencia Apache-2.0 (ver `ocr/`).
