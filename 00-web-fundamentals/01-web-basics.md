# Fundamentos Web

## 1. ¿Qué es una aplicación web?
Una aplicación web es software que utiliza las capacidades del navegador para proporcionar una experiencia interactiva al usuario.
## 2. ¿Qué función cumple el navegador?
El navegador interpreta y ejecuta HTML, CSS y JavaScript y proporciona las APIs necesarias para que una aplicación web funcione.
## 3. ¿Cuál es la responsabilidad de HTML?
HTML describe la estructura y el significado del contenido.
Por ejemplo:
```html
<header>
<nav>
<main>
<article>
<section>
<footer>
```

## 4. ¿Cuál es la responsabilidad de CSS?
Sirve para configurar personalizar el aspecto que tendrá la estructura de HTML.
Por ejemplo:
- layout
- tamaño
- espaciado
- posición
- responsive
- animaciones
- transiciones
- grid
- flexbox
- etc.

## 5. ¿Cuál es la responsabilidad de JavaScript?
Le agrega el comportamiento al sitio web en la parte visual.
Por ejemplo: 
- lógica
- datos
- eventos
- networking
- validaciones
- estado
- cálculos
- manipulación del DOM
- etc.

## 6. ¿Qué ocurre aproximadamente cuando escribo una URL en el navegador?
Le estás pasando la dirección web del recurso al que quieres acceder por medio del navegador.
El flujo consiste en lo siguiente:
URL
 ↓
DNS
 ↓
Servidor
 ↓
HTTP request
 ↓
HTTP response
 ↓
Browser
 ↓
Renderizado

## 7. ¿Qué es HTTP?
El protocolo mediante el cual clientes y servidores intercambian recursos y mensajes en la Web.

## 8. ¿Qué es una API?
Sirve como una interfaz de comunicación entre dos sistemas distintos (cliente y servicio) con esta se puede generar la interacción entre ambas partes
## 9. ¿Qué diferencia conceptual encuentras entre una aplicación Android
La aplicación móvil de android es un programa local que corre en tu celular android y que utiliza protocolos de comunicación, como puede ser Rest, GraphQL o soap para comunicarse con un backend.
La aplicación web es un programa que tienes que utilizar por medio del navegador y dicho programa lo bajas del servidor web para utilizarlo. Una aplicación web no necesariamente tiene que descargar todo desde el servidor cada vez.
## 10. Relación con Android
Con las tecnologías correctas puedes convertir una página web en una aplicación móvil que corra localmente en el celular sin necesidad de utilizar el navegador como medio de uso.

¿Qué conceptos de Android que ya conoces crees que podrían tener algún equivalente en Web? Clientes Api, botones, imágenes, tipos de variables, patrones de diseño, backend, etc.

| Android    | Web                           |
| ---------- | ----------------------------- |
| Compose    | React                         |
| Composable | React Component               |
| State      | React State                   |
| ViewModel  | No existe equivalente directo |
| Retrofit   | `fetch` / cliente HTTP        |
| Kotlin     | JavaScript / TypeScript       |
| XML        | HTML                          |
| Modifier   | CSS                           |
| LazyColumn | Lista/virtualización en React |
| Navigation | React/Next.js routing         |
| Gradle     | npm/pnpm tooling              |
| APK        | Bundle/build web              |
| Activity   | No existe equivalente directo |
| Fragment   | No existe equivalente directo |
