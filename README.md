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
