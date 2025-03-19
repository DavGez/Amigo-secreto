let listaAmigos = [];

function agregarNombre() {
  let nombreInput = document.getElementById('nombreInput');
  let nombre = nombreInput.value.trim();

  if (nombre === "") {
    alert("Por favor, ingresa un nombre válido.");
    return;
  }

  listaAmigos.push(nombre);
  mostrarLista();
  nombreInput.value = ""; // Limpiar el campo de texto
}

function mostrarLista() {
  let listaElement = document.getElementById('listaAmigos');
  listaElement.innerHTML = "";

  listaAmigos.forEach(function(nombre) {
    let li = document.createElement('li');
    li.textContent = nombre;
    listaElement.appendChild(li);
  });
}

function sortearAmigo() {
  if (listaAmigos.length === 0) {
    alert("La lista está vacía. Añade algunos nombres primero.");
    return;
  }

  let indexAleatorio = Math.floor(Math.random() * listaAmigos.length);
  let amigoSecreto = listaAmigos[indexAleatorio];

  let resultadoElement = document.getElementById('resultado');
  resultadoElement.textContent = "El amigo secreto es: " + amigoSecreto;
}
