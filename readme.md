MANERAS DE VINCULAR HTML CON CSS
Existen 3 formas de vincular HTML con CSS:
    1. En linea, es cuando se agrega el atributo style.
    Ejm: <p style="color: blue; font-size: 16px;">Este es un párrafo azul con un tamaño de fuente de 16px.</p>
    2. De forma interna, utilizando la etiqueta <style> en la seccion de <head>.
    Ejm: 
    <head>
    <style>
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        p {
            color: blue;
            font-size: 16px;
        }
    </style>
</head>
    3. De forma excterna, esto mediante un archivo de extension .css . Es la opción más recomendada.
    Ejm: <link rel="stylesheet" href="styles.css">

CONJUNTO DE REGLAS DE CSS
SELECTOR : Apunta a elementos de HTML en los que se les aplicarán los estilos.
    Ejm: h1 , body 
PROPIEDAD : Son los atributos aplicados al elemento seleccionado.
    Ejm : color, font-size
VALOR : Son configuraciones especificas aplicadas a las propiedades.
    Ejma : red, 30px