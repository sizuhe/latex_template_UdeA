# Plantilla de tesis - UdeA
Esta plantilla es una reorganización de la plantilla publicada en la Biblioteca Digital de la Universidad de Antioquia. Conserva el estilo y formato de la versión original, pero introduce cambios significativos en la estructura y organización de los archivos. Además, incorpora nuevas funcionalidades y corrige diversos errores presentes en la versión anterior.

> [!IMPORTANT]
> Aunque esta plantilla mantiene el mismo estilo y formato de la vieja plantilla, NO representa una actualización oficial de la misma. 
> - **Plantilla original**: [https://bibliotecadigital.udea.edu.co/handle/10495/10599](https://bibliotecadigital.udea.edu.co/handle/10495/10599)


## Cambios
- Se corrigen errores relacionados con los paquetes y la clase del documento presentes en la plantilla original.
- Se solucionan los problemas de la tabla de contenido cuando el documento contiene un gran número de títulos.
- Se corrigen errores de compilación.
- Se simplifica la estructura de archivos y se eliminan archivos innecesarios.
- Se agrega la capacidad de traducir los textos predeterminados de la plantilla al idioma inglés.
- Se simplifica el texto guía.
- Automatización de diferentes textos de la plantilla según la información del archivo `metadata.tex`.


## Instrucciones de uso
En el archivo `main.tex` se encuentra la estructura principal del documento y algunas variables que deben ser definidas por el usuario, como el título de la tesis, el nombre del autor, el programa académico, entre otros.

1. Descargar la plantilla desde el repositorio de GitHub.
2. Para usarla en Overleaf, suba el archivo descargado .zip a su proyecto de Overleaf y descomprímalo.
3. Editar los archivos de la plantilla según sea necesario para su tesis.

### Archivos modificables
El resto de archivos que no se mencionen a continuación no deben ser modificados, ya que son archivos de configuración y estilo de la plantilla. Los archivos modificables son:
- `config/metadata.tex`: contiene información de la tesis, como el título, autor, programa académico, entre otros. Esta información se utiliza para generar automáticamente la portada, la página legal y otros textos del documento. Desde aqui se puede seleccionar el idioma del documento (español o inglés).
- `frontmatter/[2]-Dedicatoria.tex`: contiene el texto de la dedicatoria y agradecimientos.
- `frontmatter/[4]-Nomenclatura.tex`: contiene la lista de abreviaturas y símbolos utilizados en el documento.
- `main.tex`: contiene la estructura principal del documento y las referencias a los archivos de las secciones. Aquí se deben agregar o eliminar las referencias a los archivos de las secciones según sea necesario.
- `sections/`: contiene los archivos de las secciones del documento. Se recomienda agregar los nuevos archivos .tex a esta carpeta y referenciarlos en el archivo `main.tex` con la ruta relativa.
- `imgs/`: contiene las imágenes utilizadas en el documento. Se recomienda agregar las imágenes a esta carpeta y referenciarlas en el documento con la ruta relativa.
- `bibliography.bib`: contiene las referencias bibliográficas del documento.

> [!TIP]
> El repositorio [https://github.com/sizuhe/latex_templates_library](https://github.com/sizuhe/latex_templates_library) contiene instrucciones para el uso de Docker y LaTeX, así como una guía para la instalación de los paquetes necesarios para compilar documentos en LaTeX.


## Recomendaciones
- Agregar las imagenes a la carpeta `imgs` y referenciarlas en el documento con la ruta relativa. Igualmente, se recomienda agregar los nuevos archivos .tex a la carpeta `sections` y referenciarlos en el documento principal con la ruta relativa.
- Agregar archivos con nombres secuenciales como [1]-Archivo1, [2]-Archivo2, etc. a la carpeta `sections` y referenciarlos en el documento principal con la ruta relativa.
