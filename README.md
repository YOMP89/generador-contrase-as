# Generador de Contraseñas

Este proyecto es un generador de contraseñas simple pero efectivo, creado con HTML, CSS y JavaScript. Permite a los usuarios generar contraseñas seguras con opciones personalizables.

## Características

- Genera contraseñas seguras
- Permite seleccionar la longitud de la contraseña (entre 8 y 32 caracteres)
- Opciones para incluir mayúsculas, minúsculas, números y símbolos
- Botón para copiar la contraseña generada al portapapeles

## Cómo usar

1. Abre el archivo `index.html` en tu navegador web.
2. Selecciona la longitud deseada para tu contraseña.
3. Marca o desmarca las opciones según tus preferencias:
   - Mayúsculas
   - Minúsculas
   - Números
   - Símbolos
4. Haz clic en el botón "Generar Contraseña".
5. La contraseña generada aparecerá en el campo de texto.
6. Para copiar la contraseña, haz clic en el botón "Copiar".

## Estructura del proyecto

- `index.html`: Contiene la estructura HTML de la página.
- `styles.css`: Contiene los estilos CSS para dar formato a la página.
- `script.js`: Contiene la lógica JavaScript para generar las contraseñas y manejar la interacción del usuario.

## Personalización

Puedes personalizar fácilmente el aspecto del generador de contraseñas modificando el archivo `styles.css`. Para cambiar la lógica de generación de contraseñas o agregar nuevas características, edita el archivo `script.js`.

## Seguridad

Este generador de contraseñas utiliza el método `Math.random()` de JavaScript para generar números aleatorios. Aunque es suficiente para uso general, ten en cuenta que no es criptográficamente seguro. Para aplicaciones que requieran un nivel más alto de seguridad, considera usar la API Web Crypto.


