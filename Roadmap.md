# 🗺️ Roadmap — Desarrollo Frontend Web con Viajia

## 🎯 Objetivo general

Desarrollar las competencias necesarias para construir aplicaciones **frontend web modernas, responsive y profesionales**, utilizando **Viajia** como proyecto principal de aprendizaje y portafolio.

La aplicación deberá funcionar correctamente en:

* Navegadores de escritorio.
* Navegadores en dispositivos móviles.
* Diferentes tamaños de pantalla.
* Diferentes métodos de interacción, incluyendo mouse, teclado y touch.

El objetivo profesional es pasar de:

> Android Developer

a:

> Android Developer con capacidad para desarrollar aplicaciones frontend web modernas.

Y conseguir que Viajia sea suficientemente sólido como para utilizarlo como proyecto de portafolio al postularse también a posiciones de **Frontend/Web Developer**.

---

# 🧱 Stack principal

El stack principal de Viajia será:

```text
HTML
  ↓
CSS
  ↓
Tailwind CSS
  ↓
JavaScript
  ↓
TypeScript
  ↓
React
  ↓
Vite
  ↓
React Router
  ↓
Axios
```

Herramientas complementarias:

```text
Vitest
React Testing Library
Playwright
React Hook Form
Zod
```

El objetivo no es aprender todas las tecnologías desde el principio, sino incorporarlas conforme aparezcan los problemas que resuelven.

---

# 0. Fundamentos de la Web

## Objetivo

Construir un modelo mental correcto de cómo funciona una aplicación web ejecutándose dentro de un navegador.

## Temas

* Qué es una aplicación web.
* Navegadores.
* Cliente y servidor.
* URL.
* DNS.
* HTTP / HTTPS.
* Request / Response.
* HTTP methods.
* HTTP status codes.
* Headers.
* APIs.
* JSON.
* DOM.
* Web APIs.
* Browser DevTools.
* Cookies.
* Local Storage.
* Session Storage.
* Diferencias entre Web y Android.

## Viajia

Comprender conceptualmente:

```text
Usuario
   ↓
Navegador
   ↓
Frontend Viajia
   ↓
API
```

El backend no forma parte de nuestro desarrollo, pero necesitamos comprender cómo se comunica nuestro frontend con él.

---

# 1. HTML

## Objetivo

Aprender a construir la estructura semántica de una aplicación web.

## Temas

### Anatomía

* Estructura de un documento HTML.
* `<!DOCTYPE html>`.
* `html`.
* `head`.
* `body`.
* Metadata.

### Elementos

* Headings.
* Párrafos.
* Links.
* Imágenes.
* Botones.
* Listas.
* Tablas.
* `div`.
* `span`.

### Formularios

* `form`.
* `input`.
* `label`.
* `select`.
* `option`.
* `textarea`.
* Checkbox.
* Radio buttons.
* Submit.
* Validación HTML.

### HTML semántico

* `header`.
* `nav`.
* `main`.
* `section`.
* `article`.
* `aside`.
* `footer`.

### Otros conceptos

* Atributos.
* `id`.
* `class`.
* `data-*`.
* DOM.
* Metadata.
* Accesibilidad básica.

## 🛠️ Aplicación en Viajia

Construir la estructura semántica de las pantallas de Viajia sin preocuparnos todavía por reproducir completamente el diseño visual.

---

# 2. CSS

## Objetivo

Comprender el sistema visual de la Web antes de utilizar Tailwind CSS.

> Tailwind no sustituye el conocimiento de CSS. Es una herramienta que nos permite trabajar con CSS mediante clases utilitarias.

## Temas

### Fundamentos

* Selectores.
* Cascada.
* Especificidad.
* Herencia.
* Box Model.
* `box-sizing`.
* Unidades.
* Colores.
* Tipografía.

### Layout

* `display`.
* Block.
* Inline.
* Flexbox.
* CSS Grid.
* Positioning.
* `overflow`.
* `z-index`.
* Stacking contexts.

### Responsive Design

* Mobile-first.
* Breakpoints.
* Media queries.
* Responsive layouts.
* Responsive typography.
* Responsive images.
* `min-width`.
* `max-width`.

### CSS moderno

* CSS Custom Properties.
* `calc()`.
* `clamp()`.
* Container Queries.
* `aspect-ratio`.

### Efectos visuales

* Borders.
* Border radius.
* Shadows.
* Gradients.
* Opacity.
* Transform.
* Transitions.
* Animations.
* Filters.
* `backdrop-filter`.

## 🛠️ Aplicación en Viajia

Aprender a transformar:

```text
Figma
  ↓
Layout
  ↓
CSS
  ↓
Interfaz responsive
```

---

# 3. Tailwind CSS

## Objetivo

Aprender Tailwind CSS y utilizarlo como sistema principal de estilos de Viajia.

El diseño actual de Viajia utiliza conceptos propios de un **design system**, incluyendo:

* colores;
* tipografías;
* spacing;
* border radius;
* tamaños;
* márgenes;
* superficies;
* estados visuales.

## Temas

### Fundamentos

* ¿Qué es Tailwind CSS?
* Utility-first CSS.
* Utility classes.
* Responsive modifiers.
* Variants.
* States.
* Arbitrary values.

### Layout

* Flex.
* Grid.
* Gap.
* Padding.
* Margin.
* Width.
* Height.
* Positioning.
* Overflow.

### Typography

* Font family.
* Font size.
* Font weight.
* Line height.
* Letter spacing.

### Visuales

* Colors.
* Backgrounds.
* Borders.
* Radius.
* Shadows.
* Opacity.
* Gradients.

### Responsive Design

* Mobile-first.
* Breakpoints.
* Responsive utilities.
* Desktop/mobile variants.

### Configuración

* Theme.
* Custom colors.
* Custom spacing.
* Typography.
* Fonts.
* Design tokens.
* Configuration.

### Componentización

* Tailwind + React.
* Reutilización de estilos.
* Variantes.
* Component states.

## 🛠️ Viajia

Convertir el sistema visual de Figma en nuestro sistema de estilos:

```text
Figma
  ↓
Design Tokens
  ↓
Tailwind CSS
  ↓
React Components
```

---

# 4. JavaScript moderno

## Objetivo

Aprender JavaScript desde los fundamentos hasta tener una base suficiente para trabajar profesionalmente con React.

Debido a que JavaScript será prácticamente nuevo para nosotros, este módulo tendrá especial importancia.

## Fundamentos

* Variables.
* `let`.
* `const`.
* Tipos.
* Strings.
* Numbers.
* Boolean.
* `null`.
* `undefined`.
* Arrays.
* Objects.
* Operators.
* Comparaciones.

## Funciones

* Functions.
* Parameters.
* Return.
* Arrow functions.
* Scope.
* Closures.

## Arrays y objetos

* `map`.
* `filter`.
* `find`.
* `some`.
* `every`.
* `reduce`.
* Destructuring.
* Spread.
* Rest.

## Sintaxis moderna

* Template literals.
* Optional chaining.
* Nullish coalescing.
* Default parameters.

## Módulos

* ES Modules.
* `import`.
* `export`.

## Web APIs

* DOM.
* Events.
* Event listeners.
* Local Storage.
* Fetch.
* JSON.
* URL APIs.

## Asincronía

* Promises.
* `async`.
* `await`.
* Error handling.
* Event loop.

## 🛠️ Viajia

Crear pequeños ejercicios independientes:

* búsqueda;
* filtros;
* favoritos;
* likes;
* selección;
* manipulación de datos.

---

# 5. TypeScript

## Objetivo

Aprender TypeScript como lenguaje principal para el desarrollo del frontend de Viajia.

## Temas

* Type inference.
* Primitive types.
* Arrays.
* Objects.
* Interfaces.
* Type aliases.
* Union types.
* Intersection types.
* Optional properties.
* Generics.
* Type narrowing.
* Type guards.
* `unknown`.
* `never`.
* `any`.
* Utility types.
* Function typing.
* Object typing.
* API typing.
* Type assertions.
* Discriminated unions.

## 🛠️ Viajia

Modelar las principales entidades:

```text
User
Event
Place
Post
Comment
Transport
Itinerary
Notification
Message
```

---

# 6. React

## Objetivo

Aprender el modelo moderno de construcción de interfaces mediante componentes.

## Fundamentos

* Componentes.
* JSX.
* TSX.
* Props.
* State.
* Events.
* Conditional rendering.
* Lists.
* Keys.
* Component composition.

## Hooks

* `useState`.
* `useEffect`.
* `useRef`.
* `useMemo`.
* `useCallback`.
* `useContext`.
* Custom hooks.

## UI

* Controlled components.
* Component states.
* Loading states.
* Error states.
* Empty states.
* Conditional UI.
* Derived state.

## 🛠️ Viajia

Crear componentes como:

```text
Navbar
EventCard
PostCard
UserCard
Profile
SearchBar
Filter
Modal
Dialog
Tabs
Notification
Message
```

---

# 7. Vite

## Objetivo

Aprender a utilizar Vite como herramienta de desarrollo y build de nuestra aplicación React.

## Temas

* ¿Qué es Vite?
* Development server.
* Hot Module Replacement.
* Build.
* Production build.
* `package.json`.
* Scripts.
* Assets.
* Environment variables.
* `.env`.
* TypeScript + Vite.
* React + Vite.
* Configuración básica.

## Resultado

Crear la aplicación real:

```text
React
+
TypeScript
+
Vite
+
Tailwind CSS
```

---

# 8. Routing

## Tecnología

React Router.

## Objetivo

Aprender a manejar la navegación de una aplicación SPA.

## Temas

* Routes.
* Navigation.
* Links.
* Nested routes.
* Dynamic routes.
* Route parameters.
* Query parameters.
* Not Found.
* Navigation state.
* Protected routes.

## 🛠️ Viajia

Implementar rutas como:

```text
/
├── /events
├── /events/:id
├── /explore
├── /transport
├── /profile/:id
├── /itinerary
├── /messages
└── /notifications
```

---

# 9. Comunicación con APIs

## Tecnología

Axios.

## Objetivo

Aprender a consumir APIs desde una aplicación frontend.

## Temas

* HTTP desde frontend.
* Axios.
* GET.
* POST.
* PUT.
* PATCH.
* DELETE.
* Query parameters.
* Request body.
* Headers.
* Responses.
* HTTP errors.
* Error handling.
* Axios instances.
* Interceptors.
* Authentication headers.
* `FormData`.

## Arquitectura

```text
React
  ↓
Hook / Logic
  ↓
Service
  ↓
Axios
  ↓
API
```

## 🛠️ Viajia

Crear servicios como:

```text
eventService
userService
postService
transportService
itineraryService
```

Durante el desarrollo inicial podremos utilizar APIs mockeadas o datos locales.

---

# 10. Estado y datos

## Objetivo

Aprender a identificar y manejar correctamente los diferentes tipos de estado de una aplicación frontend.

## Temas

* Local state.
* UI state.
* Form state.
* URL state.
* Server state.
* Global state.
* Derived state.
* State normalization.
* Immutable updates.
* Async state.
* Loading.
* Error.
* Empty.
* Optimistic UI.

## 🛠️ Viajia

Aplicarlo a:

* filtros;
* favoritos;
* publicaciones;
* itinerarios;
* notificaciones;
* mensajes;
* selección de elementos;
* mapas.

---

# 11. Formularios

## Tecnologías

* React Hook Form.
* Zod.

## Temas

* Controlled inputs.
* Uncontrolled inputs.
* Form state.
* Validation.
* Schema validation.
* Error messages.
* Form UX.
* Accessibility.
* Multi-step forms.

## 🛠️ Viajia

* Login.
* Registro.
* Crear publicación.
* Crear evento.
* Editar perfil.
* Buscar eventos.
* Crear itinerario.

---

# 12. UI avanzada

## Objetivo

Implementar los patrones de interfaz presentes en los diseños de Viajia.

## Modales

* Dialog.
* Backdrop.
* Portal.
* Scroll locking.
* Escape key.
* Focus management.
* Accessible dialogs.

## Tabs

* Tab state.
* Active tab.
* Keyboard navigation.
* Accessible tabs.

## Uploads

* File input.
* `File`.
* `FileList`.
* Image preview.
* Object URLs.
* Multiple files.
* `FormData`.
* Upload states.
* File validation.

## Drag & Drop

* Drag & Drop API.
* Drag state.
* Drop zones.
* Reordering.
* Accessibility.

## Listas

* Pagination.
* Load more.
* Infinite scroll.
* `IntersectionObserver`.

## UX States

* Loading.
* Skeleton.
* Empty.
* Error.
* Retry.
* Success.

## 🛠️ Viajia

Aplicarlo principalmente en:

* Crear publicación.
* Crear evento.
* Itinerarios.
* Eventos.
* Notificaciones.
* Mensajes.

---

# 13. Mapas y funcionalidades geográficas

## Objetivo

Implementar la interfaz de mapas de Viajia desde el frontend.

## Temas

* Geolocation API.
* Coordinates.
* Map viewport.
* Markers.
* Selected markers.
* Popups.
* Zoom.
* Pan.
* Routes.
* Current location.
* Map/List interaction.
* Map overlays.
* Clustering.

La elección de la librería/proveedor de mapas se realizará posteriormente según las necesidades del proyecto.

## 🛠️ Viajia

Implementar las interfaces relacionadas con:

* eventos;
* lugares;
* transporte;
* rutas;
* ubicación.

---

# 14. Comunicación en tiempo real — Frontend

## Objetivo

Conocer cómo un frontend puede consumir información en tiempo real.

Este módulo se limita al **frontend**.

## Temas

* Concepto de WebSockets.
* Browser WebSocket API.
* Connection state.
* Reconnection.
* Events.
* Real-time UI.
* Optimistic UI.
* Presence.

## 🛠️ Viajia

Principalmente:

* mensajes;
* estado online;
* notificaciones.

Si el backend todavía no está disponible, estas funcionalidades podrán simularse.

---

# 15. Accesibilidad Web

## Objetivo

Construir interfaces utilizables por la mayor cantidad posible de usuarios.

## Temas

* Semantic HTML.
* ARIA.
* Keyboard navigation.
* Focus.
* Focus management.
* Screen readers.
* Accessible names.
* Contrast.
* Accessible forms.
* Accessible buttons.
* Accessible dialogs.
* Accessible tabs.
* WCAG.

La accesibilidad se aplicará progresivamente durante el desarrollo, no solamente al finalizar.

---

# 16. Responsive Web Design

Aunque responsive design ya aparece durante CSS y Tailwind, tendrá una revisión específica sobre la aplicación completa.

## Temas

* Mobile-first.
* Desktop layouts.
* Mobile layouts.
* Breakpoints.
* Responsive components.
* Responsive navigation.
* Horizontal scrolling.
* Responsive grids.
* Touch-friendly controls.
* Sticky elements.
* Fixed elements.
* Overflow.
* Viewport behavior.

## 🛠️ Viajia

La aplicación deberá adaptarse a:

```text
Desktop
Tablet
Mobile
```

Manteniendo la funcionalidad y usabilidad.

---

# 17. Design System y arquitectura de componentes

## Objetivo

Aprender a convertir el diseño de Figma en un sistema de componentes reutilizables.

## Temas

* Design tokens.
* Colors.
* Typography.
* Spacing.
* Border radius.
* Shadows.
* Component variants.
* Component states.
* Reusable components.
* Component API.
* Naming.
* Composition.
* Shared components.
* Feature components.

## 🛠️ Viajia

Convertir:

```text
Figma
  ↓
Design Tokens
  ↓
Tailwind
  ↓
React Components
```

Posible estructura:

```text
src/
├── components/
├── features/
├── hooks/
├── services/
├── types/
├── pages/
├── routes/
├── utils/
└── assets/
```

La estructura definitiva se decidirá durante la implementación.

---

# 18. Testing Frontend

## Unit testing

### Vitest

Probar:

```text
función
  ↓
input
  ↓
resultado esperado
```

## Component testing

### React Testing Library

Probar:

```text
Usuario
  ↓
Interacción
  ↓
UI
  ↓
Resultado
```

## End-to-End

### Playwright

Probar:

```text
Usuario
  ↓
Navegador
  ↓
Viajia
  ↓
Flujo completo
```

## Temas

* Unit tests.
* Component tests.
* Integration tests.
* E2E.
* Mocks.
* Fixtures.
* Test doubles.
* Coverage.
* Testing strategy.
* Qué probar.
* Qué no probar.
* Testing de errores.
* Testing de accesibilidad.

---

# 19. Performance Web

## Objetivo

Aprender a medir y optimizar el rendimiento de una aplicación frontend.

## Temas

* Rendering.
* Re-rendering.
* Bundle size.
* Code splitting.
* Lazy loading.
* Images.
* Image optimization.
* Fonts.
* Caching.
* Network performance.
* Core Web Vitals.
* React performance.
* Memoization.

## 🛠️ Viajia

Prestar especial atención a:

* imágenes de eventos;
* imágenes de perfiles;
* mapas;
* listas;
* feeds;
* carga progresiva.

---

# 20. Seguridad Frontend

## Objetivo

Conocer los principales riesgos de seguridad relacionados con aplicaciones ejecutadas en el navegador.

## Temas

* XSS.
* CSRF.
* CORS.
* Content Security Policy.
* Environment variables.
* Secrets.
* Dependency security.
* Supply-chain attacks.
* Input validation.
* Authentication basics.
* Token handling.

## Alcance

No estudiaremos seguridad de servidores, bases de datos o infraestructura.

El enfoque será:

> **¿Qué debe saber un frontend developer para construir una aplicación web más segura?**

---

# 21. Portfolio

## Objetivo

Convertir Viajia en una demostración profesional de nuestras competencias frontend.

## Documentaremos

* Problema que resuelve Viajia.
* UX/UI.
* Stack tecnológico.
* Arquitectura.
* Componentes.
* Design System.
* Responsive Design.
* Consumo de APIs.
* Testing.
* Accesibilidad.
* Performance.
* Seguridad.
* Decisiones técnicas.
* Problemas encontrados.
* Soluciones.
* Screenshots.
* Demo.
* README.
* Aprendizajes.

## Presentación profesional

El proyecto deberá permitir presentar una experiencia como:

> **Android Developer con experiencia en desarrollo frontend web utilizando React, TypeScript, Vite, Tailwind CSS y Axios.**

---

# 🚫 Tecnologías y temas fuera del alcance

Para mantener el proyecto enfocado en frontend web, no serán parte del roadmap principal:

* Desarrollo Android.
* Desarrollo iOS.
* React Native.
* Flutter.
* Backend.
* Spring Boot.
* Node.js backend.
* Bases de datos.
* Docker.
* Kubernetes.
* Infraestructura Cloud.
* DevOps.
* CI/CD.
* Deployment.
* Server-side rendering.
* Next.js.
* Arquitectura de servidores.

Podremos mencionar o estudiar brevemente alguna de estas tecnologías cuando sea necesario para comprender una integración, pero no serán objetivos del curso.

---

# 🔧 Conocimientos previos

## Git

Ya contamos con conocimientos básicos de:

* Git.
* Branches.
* Commits.
* GitLab.

Por lo tanto, **no se incluye un módulo de aprendizaje de Git**.

Lo utilizaremos durante todo el proyecto.

## DevOps

El proyecto contará con apoyo de otro integrante para:

* CI/CD.
* Deployment.
* Infraestructura.
* DevOps.

Por lo tanto, estos temas **no forman parte del roadmap de aprendizaje frontend**.

---

# 🧭 Ruta principal de aprendizaje

La secuencia principal será:

```text
HTML
  ↓
CSS
  ↓
Tailwind CSS
  ↓
JavaScript
  ↓
TypeScript
  ↓
React
  ↓
Vite
  ↓
React Router
  ↓
Axios
  ↓
Estado y datos
  ↓
Formularios
  ↓
UI avanzada
  ↓
Mapas
  ↓
Design System
  ↓
Testing
  ↓
Accesibilidad
  ↓
Performance
  ↓
Seguridad
  ↓
Portfolio
```

Los conocimientos transversales se irán aplicando durante todo el proceso:

```text
Responsive Design
Accessibility
Testing
Performance
Security
Component Architecture
```

---

# 📚 Metodología de aprendizaje

No aprenderemos cada tecnología completamente aislada para después comenzar Viajia.

Utilizaremos un ciclo:

```text
📚 Aprender concepto
       ↓
🧪 Ejercicio pequeño
       ↓
🌎 Aplicarlo a Viajia
       ↓
📝 Documentarlo en Knowledge Bank
       ↓
➡️ Siguiente concepto
```

La documentación del **Knowledge Bank** contendrá los conceptos generales que puedan reutilizarse en futuros proyectos.

La documentación específica de Viajia permanecerá dentro del repositorio del proyecto.

---

# 🎯 Resultado final esperado

Al finalizar Viajia deberíamos ser capaces de:

* Construir interfaces web semánticas con HTML.
* Crear diseños responsive con CSS.
* Utilizar Tailwind CSS profesionalmente.
* Programar en JavaScript moderno.
* Desarrollar aplicaciones con TypeScript.
* Construir interfaces con React.
* Utilizar Vite.
* Implementar navegación con React Router.
* Consumir APIs utilizando Axios.
* Manejar diferentes tipos de estado.
* Crear formularios complejos.
* Implementar componentes reutilizables.
* Trabajar con mapas.
* Implementar patrones de UI avanzados.
* Escribir tests frontend.
* Crear interfaces accesibles.
* Optimizar aplicaciones web.
* Conocer fundamentos de seguridad frontend.
* Traducir diseños de Figma a código.
* Trabajar con un Design System.
* Construir una aplicación responsive para desktop y mobile web.

Y, sobre todo:

> **Ser capaz de explicar no solamente cómo construir un frontend web, sino por qué se toman determinadas decisiones técnicas.**
