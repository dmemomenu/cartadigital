# DMEMO Fast Food — Carta digital interactiva

Sitio ecommerce con los datos de DMEMO Fast Food (Villa María del Triunfo), 47 entradas de menú, opciones de cremas, adicionales exclusivos de hamburguesa y salsas para alitas, carrito y pedido por WhatsApp.

## Abrirlo

1. Extrae el archivo ZIP; no subas el ZIP como tal a GitHub.
2. La carpeta tiene **cuatro archivos principales** (`index.html`, `styles.css`, `script.js`, `README.md`) y **una carpeta** `img/` con las fotografías.
3. Puedes abrir `index.html` en tu computadora para explorar; para compartirlo en línea, súbelo a un repositorio GitHub y conecta ese repositorio a Cloudflare Pages.
4. En GitHub elige **Add file → Upload files**, arrastra **los cuatro archivos y la carpeta `img/`**, y luego presiona **Commit changes**. Si tu navegador no permite arrastrar una carpeta, arrastra los archivos de la carpeta conservando la ruta `img/` usando la opción de carga compatible o GitHub Desktop.

## Cambiar platos, precios o fotografías

- **Platos y precios:** están al inicio de `script.js` en `const MENU`. Busca el plato y cambia `price:11` por el precio nuevo.
- **Fotografías:** reemplaza la imagen JPG correcta en la carpeta `img/`. Los nombres están enlazados desde la tabla `PRODUCT_IMAGE_FILES` en `script.js`.
- **WhatsApp y dirección:** cambia `whatsapp` o `address` al comienzo de `script.js`.

## Avisos para publicar

- Las fotografías son imágenes **generadas / ilustrativas**, no fotografías reales de los productos del local. Comprueba ingredientes y tamaño de porción contra lo que vende el restaurante. Algunas opciones como gaseosa de diferente tamaño y versiones frozen comparten la foto base de la bebida.
- Los pagos Yape, Plin, efectivo, transferencia y contraentrega son **modalidades informativas**, no cobros automáticos integrados.
- El botón de WhatsApp abre un mensaje prellenado; la persona debe pulsar **Enviar** dentro de WhatsApp y el restaurante debe confirmar el pedido, el costo de delivery, pago y disponibilidad.
- GitHub puede alojar el **código**; para publicar una web comercial es recomendable Cloudflare Pages y revisar las condiciones del proveedor.

## Datos de DMEMO

- WhatsApp: +51 902 058 990
- Dirección: Ucayali 380, Villa María del Triunfo 15822
- Google Maps: https://www.google.com/maps?q=-12.2145796,-76.9092452&z=17&hl=es

---

## Actualización DMEMO — 05/11/2026

### Correcciones incluidas

- WhatsApp de pedidos y enlaces de consulta: **+51 989 580 237** (`51989580237`). El mensaje se arma como texto UTF-8 y se codifica con `URLSearchParams`.
- Dirección de recojo y contacto: **Ucayali 356, Villa María del Triunfo, Lima**. El mapa busca la nueva dirección por texto; **comprobar el pin exacto en Google Maps antes de publicar**.
- Los nueve adicionales configurados están disponibles en **todos los platos salvo bebidas**, suman precio y aparecen en el carrito y en el mensaje de WhatsApp.
- Promoción **Lunes Zapatero**: Burguer Clásica a **S/ 8.00 los lunes** (hora de Lima, zona `America/Lima`). Fuera del lunes, el precio normal vuelve a **S/ 11.00**. El banner animado se mantiene visible como anuncio semanal.
- Se agregan **Salchi Nuggets** (S/ 17), **Jugo Especial** (S/ 15), **Maracumango** (S/ 13) y **Fresa con Leche** (S/ 15).
- Las descripciones de alitas muestran cantidad conocida y opciones de salsa. La **Ronda de Alitas** mantiene su cantidad como **«por confirmar»**, pues no se proporcionó un número de piezas.
- Actualización y corrección de fotografías de chaufas, mostritos, mollejitas, filete a la plancha, jugos y gaseosas. La foto de chaufa de pollo fue facilitada por el cliente.
- Se quitó Sprite de la fotografía de gaseosas. Las variantes siguen siendo solo Inca Kola y Coca-Cola.
- Caché de CSS/JS e imágenes actualizado con versión `20261105`.

### Imágenes referenciales y pendientes

Las fotografías y collages de varios platos fueron **adaptados a partir de las imágenes ya incluidas en el proyecto original y de la referencia de chaufa compartida por el cliente**. No son fotografías tomadas de las preparaciones reales de DMEMO; es recomendable reemplazarlas con fotografías propias del restaurante cuando estén disponibles, sobre todo **Salchi Nuggets, Mollejitas, Maracumango y jugos**. No se añadieron fotografías de terceros con licencias dudosas.

### Instalación en GitHub Pages

1. Descomprime el ZIP y entra a la carpeta extraída.
2. En el repositorio, reemplaza los archivos de la raíz `index.html`, `styles.css`, `script.js` y `README.md`.
3. En la carpeta **`img/`**, reemplaza las fotografías modificadas e **incluye los cuatro archivos JPG nuevos**: `salchi-nuggets.jpg`, `jugo-especial.jpg`, `jugo-maracumango.jpg` y `jugo-fresa-leche.jpg`. La ruta `img/` debe conservarse.
4. Confirma los cambios (commit) y revisa GitHub Pages en móvil y escritorio.
5. Revisa el mapa (dirección exacta), un pedido con adicionales, una bebida sin adicionales y la previsualización de WhatsApp antes de atender pedidos reales.

No se ha publicado ningún cambio en el repositorio remoto; el proyecto actualizado está en este ZIP.
