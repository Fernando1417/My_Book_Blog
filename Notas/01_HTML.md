# Definición básica de HTML

Establecí la base mínima de una página web con una referencia a los estilos CSS.

Código base con las etiquetas `<head>` y `<body>`.

```html
<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <link rel="icon" type="image/png" href="images/book.png">
    <link rel="stylesheet" href="styles.css">
    <title>My Book Blog</title>
  </head>
  <body>

    <h1>My Book Blog</h1>
    <p class="test-class">Welcome to my book blog!</p>
  </body>
</html>
```

```css
.test-class {
  color: blue;
}
```

## Exploración

Elementos que agregué en la etiqueta `<head>` para configurar aspectos de la página web.

**Codificación de caracteres**

```html
<meta charset="UTF-8">
```

Indica que la página utiliza la codificación **UTF-8**, que permite mostrar correctamente letras, tildes, la `ñ`, símbolos y caracteres de distintos idiomas.

**Ícono de la página**

```html
<link rel="icon" type="image/png" href="images/book.png">
```

Define el **favicon**, es decir, el pequeño ícono que aparece en la pestaña del navegador.

*   `rel="icon"`: indica que el archivo es el ícono de la página.
*   `type="image/png"`: especifica que la imagen está en formato PNG.
*   `href="images/book.png"`: señala la ubicación del archivo.