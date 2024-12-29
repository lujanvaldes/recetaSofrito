# receta Sofrito

*Objetivo de la actividad:* reforzar el uso de la web semántica creando una página detallada de una receta de cocina, utilizando etiquetas HTML semánticas para organizar el contenido de manera lógica y accesible.

## Instrucciones

1. Crear un archivo HTML para la receta. Asegúrate de incluir las etiquetas básicas (<!DOCTYPE html>,   <html>, <head>, <meta charset="UTF-8">, <title>, y <body>).

2. Dale a la página un título adecuado en la etiqueta <title> (ej. "Tarta de Manzana") y crea las etiquetas <meta> necesarias para mejorar su SEO.

`Cabecera de la Web`
1. Adapta la cabecera original de tu web, utilizando la etiqueta semántica correspondiente.

`Sección Principal de la Página`

2. Usa <main> para el contenido principal de la receta.

3. Dentro de <main>, crea un <article> para encapsular la receta completa. Esto indicará que la receta es el tema principal de la página, y si alguien se llevara el artículo completo a otra web, seguiría teniendo sentido el contenido.

`Cabecera de Receta`
1. Crea una sección como cabecera de la receta que incluya el título de la receta en una etiqueta <h1>.

2. Añade el nombre del chef o autor debajo del título usando <p> o <strong>.

`Descripción de la Receta`
1. Dentro del <article>, agrega una sección (<section>) con una breve descripción de la receta (ej. “Esta tarta de manzana es una receta fácil y deliciosa…”).

2. Usa un encabezado (<h2>) para titular esta sección (ej. “Descripción”).

`Lista de Ingredientes`
1. Crea otra sección (<section>) para los ingredientes.

2. Usa un encabezado <h2> titulado “Ingredientes”.

3. Dentro de esta sección, usa una lista no ordenada (<ul>) para los ingredientes, y cada ingrediente en un <li>.

`Instrucciones de Preparación`
1. Añade una nueva sección <section> para las instrucciones de la receta.

2. Usa un encabezado <h2> titulado “Instrucciones”.

3. Dentro de esta sección, usa una lista ordenada (<ol>) para los pasos de preparación, con cada paso en un <li>.

`Imagen de la Receta`
1. Si tienes una imagen de la receta, agrégala dentro de un <figure>.

2. Usa una etiqueta <img> para la imagen y un <figcaption> para añadir una breve descripción de la imagen (ej. “Tarta de manzana recién horneada”).

`Información Adicional`
Agrega un <aside> al final de la receta con alguna información adicional como:
    1. Tiempo de preparación: puedes incluir un <p> que detalle el tiempo.
    2. Valor nutricional: (si aplica) puedes usar un <p> con calorías por porción.
    3. Otras recetas: recetas similares para acompañar este plato.

- Crea un <footer> para la página. Puedes incluir un mensaje de invitación a compartir la receta o enlaces a otras secciones de CheffConnect.