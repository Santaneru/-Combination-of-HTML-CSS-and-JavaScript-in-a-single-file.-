# -Combination-of-HTML-CSS-and-JavaScript-in-a-single-file.-
este archivo muestra como se puede confinar html css y javascript en una solo archivo y tiene notas explicativas de los encabezados

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--
        UTF-8 es un sistema de codificación de caracteres que se utiliza para representar texto en computadoras y otros dispositivos. El nombre UTF-8 proviene de "Unicode Transformation Format - 8 bits"
       
        La etiqueta meta <meta http-equiv="X-UA-Compatible" content="IE=edge"> es una directiva específica para Internet Explorer (especialmente versiones antiguas) que indica cómo el navegador debería renderizar la página web.

Vamos a descomponerlo:

http-equiv="X-UA-Compatible": El atributo http-equiv se utiliza en elementos HTML <meta> para simular una respuesta HTTP de cabecera. En este caso, X-UA-Compatible es una cabecera que Internet Explorer utiliza para determinar cómo mostrar una página.
content="IE=edge": El atributo content especifica el valor para la cabecera. En este caso, IE=edge le dice a Internet Explorer que utilice el modo de renderizado más reciente disponible en ese navegador.
La etiqueta meta <meta name="viewport" content="width=device-width, initial-scale=1.0"> es esencial para hacer que las páginas web sean responsive y se muestren adecuadamente en dispositivos móviles y tablets. Veamos en detalle:

name="viewport": Esta etiqueta meta especifica que estamos estableciendo configuraciones para el "viewport", que es el área visible de la página web en un dispositivo.
content:
width=device-width: Esta instrucción le dice al navegador que ajuste el ancho del viewport al ancho del dispositivo. En otras palabras, el ancho de la página debería ser igual al ancho del dispositivo en el que se está visualizando.
initial-scale=1.0: Define el nivel de zoom inicial cuando la página es cargada por primera vez. El valor "1.0" significa que la página se muestra al tamaño real, sin ningún tipo de zoom.-->
    <title>Mi Página</title>
    <style>
        /* CSS va aquí */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin-top: 50px;
        }
        .mi-boton {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<h1>¡Bienvenido a mi página!</h1>
<button class="mi-boton" onclick="saludar()">Haz clic en mí</button>

<script>
    // JavaScript va aquí
    function saludar() {
        alert('¡Hola, mundo!');
    }
</script>

</body>
</html>
