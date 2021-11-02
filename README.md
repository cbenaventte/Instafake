# Instafake
JWT

Descripción
Tu mejor amigo acaba de recibir una inversión para construir una idea millonaria, que
consiste en una red social de fotos, en donde todos los usuarios pueden ver, dar me gusta y
comentar las fotos. Te pide que construyas el MVP que saldrá al mercado.
El backend de la aplicación ya está construido y sólo necesitan que apliques tus habilidades
para consumir las APIs, para poder mostrar la información y darle vida a la red social. En la
siguiente imagen se muestra el resultado de la red social de fotos.

Requerimientos
1. Obtener el JWT a través del formulario de login entregado.
2. Persistir el token utilizando localStorage.
3. Al momento de recibir el JWT ocultar el formulario y mostrar el feed principal con las
fotos.
4. Con el JWT consumir la API http://localhost:3000/api/photos.
5. Manipular el JSON de respuesta de la API anterior y manipular el DOM con
JavaScript para mostrar las imágenes.
6. Cargar el feed de fotos cuando exista el JWT.
7. En la parte inferior de la página, crear un botón que al presionarlo traiga más fotos
(http://localhost:3000/api/photos?page=x), que deben ser añadidas al listado
existente.
8. Crear botón de logout que elimine el JWT almacenado y vuelva la aplicación a su
estado inicial.
