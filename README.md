# Amigo-secreto
Este repositorio es para la app de amigo secreto de alura
Sorteo de Amigo Secreto - Aplicación
Este proyecto consiste en una aplicación web para realizar un sorteo de "Amigo Secreto". Los usuarios pueden agregar nombres a una lista, visualizarla, y luego realizar un sorteo aleatorio para determinar quién será el amigo secreto de cada uno.

Funcionalidades:
Agregar Nombres: Los usuarios pueden escribir un nombre en el campo de texto y agregarlo a una lista al hacer clic en el botón "Adicionar".
Validación de Entrada: Si el campo de texto está vacío, el programa muestra una alerta solicitando un nombre válido.
Visualizar la Lista: Los nombres ingresados se muestran en una lista debajo del campo de entrada.
Sorteo Aleatorio: El usuario puede hacer clic en el botón "Sortear Amigo", y el programa seleccionará aleatoriamente un nombre de la lista, mostrándolo en la pantalla como el "Amigo Secreto".
Instrucciones de Uso
Abrir la Página: Abre el archivo index.html en tu navegador.
Agregar Nombres: Escribe los nombres de los amigos en el campo de texto y haz clic en "Adicionar" para agregarlos a la lista.
Realizar el Sorteo: Una vez que hayas añadido nombres, haz clic en "Sortear Amigo" para ver quién es el amigo secreto.
Ver el Resultado: El nombre del amigo secreto seleccionado aleatoriamente aparecerá en la parte inferior de la página.
Requisitos
Para ejecutar este proyecto, no necesitas ningún servidor o entorno de desarrollo complejo. Solo necesitas un navegador web moderno (como Chrome, Firefox, etc.).

Archivos del Proyecto:
index.html: La estructura básica de la página.
styles.css: El archivo de estilos para darle formato a la página.
script.js: El archivo que contiene el código JavaScript para manejar la lógica del sorteo.
Estructura del Proyecto
bash
Copiar
Editar
/sorteo-amigo-secreto
│
├── index.html      # Página principal
├── styles.css      # Estilos de la página
├── script.js       # Lógica de JavaScript
Descripción del Código
HTML: La estructura de la página contiene un campo de texto, un botón para agregar nombres, un contenedor para mostrar la lista de amigos y un botón para realizar el sorteo.

CSS: Estilos básicos para mejorar la apariencia de la página, como botones, lista de amigos y mensajes de resultado.

JavaScript: La lógica principal del programa. Incluye:

agregarNombre(): Agrega el nombre del amigo a la lista y valida si el campo de entrada está vacío.
mostrarLista(): Actualiza la lista visual de amigos en la página.
sortearAmigo(): Realiza el sorteo aleatorio y muestra el nombre del "Amigo Secreto".
Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Realiza un fork del repositorio.
Crea una nueva rama (git checkout -b feature-nombre).
Realiza tus cambios y haz commit (git commit -am 'Agrega una nueva característica').
Empuja a la rama (git push origin feature-nombre).
Crea un pull request.
