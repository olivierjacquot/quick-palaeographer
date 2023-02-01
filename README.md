# Paleografía rápida

Esta herramienta está basada en OpenSeadragon y Annotorious, y está pensada para ser utilizada en imágenes de manuscritos. Utilice MAYÚS-clic para dibujar cuadros delimitadores y etiquetar glifos. A continuación, abra la barra lateral de anotaciones para ver todas sus anotaciones. Aparecen en orden alfabético.

Esta herramienta fue creada como parte del proyecto Amoxcalli. La imagen del manuscrito de la demostración es cortesía de la Bibliothèque nationale de France.

![demo](demo.gif "demo")

## Uso

Paleografía rápida puede utilizarse fuera de línea, descargando todo el repositorio y abriendo el archivo `index.html` en un navegador web. Probado en las versiones actuales de Chrome y Firefox.

1. Seleccione un archivo de imagen para cargar (PNG o JPEG)
2. Utilice MAYÚS-clic para dibujar recuadros alrededor de un carácter.
3. Dale al cuadro algunas etiquetas. Puede tener más de una etiqueta.
4. Pulse OK.
5. Abre la barra lateral de anotaciones (botón en la esquina superior derecha) para ver tus anotaciones.
6. Puedes guardar tus anotaciones en formato JSON con el botón Exportar.
7. Puede volver a cargar sus anotaciones más tarde (también se guardan automáticamente).
8. Puede abrir sus anotaciones en una nueva ventana (botón en la esquina superior derecha) y luego guardar la página web completa (`Guardar página como...` en su navegador). Después puede editarla, por ejemplo, en LibreOffice Writer.

### Añadir anotaciones de varios folios

* abrir las anotaciones en una nueva ventana (botón superior derecho);
* haga clic con el botón derecho en la página y "Guardar como..." la página completa en su ordenador;
* repita el proceso para todos los folios que desee incluir;
* para el último folio, cuando abras las anotaciones en una nueva ventana, utiliza la función "añadir anotaciones" de la parte superior;
* selecciona uno de los archivos HTML que has guardado.
Guarda el archivo HTML final.  Más tarde podrás abrirlo, por ejemplo, con LibreOffice y crear un documento de referencia.


## Ejemplo

Hay una imagen de ejemplo en el directorio `example/`, junto con anotaciones. Para ver el ejemplo, descargue tanto la imagen JPEG como las anotaciones en formato JSON. Cargue la imagen en Paleografía rápida. A continuación, cargue el archivo de anotaciones con el botón Importar.

La imagen de ejemplo es el Manuscrito del aperreamiento, un manuscrito del fondo Mexicano de la BnF.
