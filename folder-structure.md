# Folder Structure

- [Spanish](#spanish)
- [English](#english)

## Spanish
### _**Explicación de la estructura de carpetas**_

```javascript
  --public
    |__ movie
        .
        .
        .
  --resource
    |__ css
    |__ img
    |__ js
```

**public**: Carpeta que almacena las plantillas, asimismo los archivos personalizados.

**resource**: Carpeta que almacena archivos de `css`, `javascript` e `imágenes` que utilizan las plantillas.

### _**Recomendaciones para crear carpetas y archivos**_

- Al momento de crear una carpeta para una plantilla, el nombre de ser en ***Ingles**.

- El primer archivo de la plantilla debe ser el `index.html`

- Para los diseños personalizados, se debe crear dentro de la plantilla que se esta usando y el archivo debe llevar el siguiente nombre `post-1.html`, el número es incrementado según la cantidad actual. (Ejemplo)

  ```javascript
    --public
      |__ movie
          |__index.html
          |__post-1.html
          |__post-2.html
          |    .
          |    .
          |    .
          |__post-n.html
  ```

- Los archivos de `css` y `js`, deben crearse con el nombre de la plantilla. (Ejemplo)

  ```javascript
    --resource
      |__ css
      |   |__movie.css
      |
      |__ js
          |__movie.js
  ```


## English
### _**Explanation of the folder structure**_

```javascript
  --public
    |__ movie
        .
        .
        .
  --resource
    |__ css
    |__ img
    |__ js
```

**public**: Folder that stores the templates, as well as the custom files.

**resource**: Folder that stores `css`, `javascript` and `images` files used by the templates.

### _**Recommendations for creating folders and files**_

- When creating a folder for a template, the name will be in **English**.

- The first file of the template must be the `index.html`.

- For custom layouts, it must be created within the template being used and the file must have the following name `post-1.html`, the number is incremented by the current amount. (Example)

  ```javascript
    --public
      |__ movie
          |__index.html
          |__post-1.html
          |__post-2.html
          |    .
          |    .
          |    .
          |__post-n.html
  ```

- The `css` and `js` files should be created with the name of the template. (Example)

  ```javascript
    --resource
      |__ css
      |   |__movie.css
      |
      |__ js
          |__movie.js
  ```