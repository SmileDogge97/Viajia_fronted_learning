# 🗺️ Roadmap — Desarrollo Frontend Web con Viajia

## 🎯 Objetivo general

Desarrollar las competencias necesarias para construir aplicaciones web modernas profesionalmente, utilizando **Viajia** como proyecto principal de aprendizaje y portafolio.

El objetivo profesional es pasar de:

> Android Developer

a:

> Android Developer con capacidad para desarrollar aplicaciones frontend web modernas.

Y que Viajia sea suficientemente sólido como para utilizarlo como proyecto de portafolio al postularse también a posiciones de Frontend/Web Developer.

---

# 📚 Roadmap

## 0. Fundamentos de la Web

**Objetivo:** entender el entorno en el que se desarrollan y ejecutan las aplicaciones web.

### Temas

- Cómo funciona la Web.
- Navegadores.
- Cliente y servidor.
- URL.
- HTTP / HTTPS.
- Request / Response.
- APIs.
- JSON.
- DOM.
- Web APIs.
- DevTools.
- Diferencias entre Web y Android.

### Resultado esperado

Tener un modelo mental correcto de cómo funciona una aplicación web.

---

## 1. HTML

**Objetivo:** aprender a construir la estructura de una página web.

### Temas

- Anatomía de un documento HTML.
- Elementos y etiquetas.
- Atributos.
- `head` / `body`.
- Textos y headings.
- Links.
- Imágenes.
- Botones.
- Listas.
- Tablas.
- Formularios.
- `div` y `span`.
- HTML semántico.
- Accesibilidad básica.
- Metadata.

### 🛠️ Aplicación en Viajia

Construir la estructura HTML de una primera pantalla de Viajia, todavía sin CSS.

---

## 2. CSS

**Objetivo:** aprender a convertir HTML en una interfaz visual.

### Temas

- Selectores.
- Cascada.
- Especificidad.
- Herencia.
- Box Model.
- Unidades.
- Colores.
- Tipografía.
- `display`.
- Positioning.
- Flexbox.
- CSS Grid.
- Overflow.
- Pseudoclases.
- Pseudoelementos.
- Variables CSS.
- Responsive Design.
- Media queries.
- Transiciones.
- Animaciones.
- Arquitectura y organización del CSS.

### 🛠️ Aplicación en Viajia

Comenzar a reproducir el diseño de Figma.

Aprender a traducir:

```text
Figma
  ↓
HTML
  ↓
CSS
  ↓
Interfaz responsive
```

## 3. JavaScript moderno

**Objetivo:** aprender el lenguaje que proporcionará comportamiento a nuestra aplicación.

### Temas

- Variables.
- Tipos.
- Arrays.
- Objetos.
- Funciones.
- Arrow functions.
- Scope.
- Closures.
- Destructuring.
- Spread/rest.
- map, filter, reduce, etc.
- Modules.
- DOM.
- Eventos.
- JSON.
- fetch.
- Promises.
- async/await.
- Manejo de errores.
- Event loop.
- Asincronía.

### 🛠️ Viajia

Añadiremos nuestras primeras interacciones:

- botones;
- filtros;
- búsqueda;
- favoritos;
- likes;
- etc.

## 4. TypeScript

**Objetivo:** pasar de JavaScript a un entorno tipado adecuado para proyectos grandes.

### Temas
- Type inference.
- Tipos primitivos.
- Interfaces.
- Type aliases.
- Union types.
- Intersection types.
- Optional properties.
- Generics.
- Type narrowing.
- Type guards.
- unknown.
- never.
- any.
- Utility types.
- Tipado de funciones.
- Tipado de objetos.
- Tipado de APIs.

### 🛠️ Viajia

Comenzaremos a modelar entidades:

- User
- Event
- Place
- Post
- Comment
- Itinerary
- Transport
- ...

## 5. React

**Objetivo:** aprender el modelo moderno de construcción de interfaces mediante componentes.

### Temas
- Componentes.
- JSX/TSX.
- Props.
- State.
- Eventos.
- Renderizado condicional.
- Listas.
- Keys.
- Component composition.
- Hooks.
- useState.
- useEffect.
- useMemo.
- useCallback.
- Context.
- Custom hooks.
- Formularios.
- Manejo de estado.

### 🛠️ Viajia

Comenzaremos a convertir nuestro diseño en componentes reales:

- Navbar
- Feed
- EventCard
- PostCard
- UserCard
- Sidebar
- ...

## 6. Next.js

**Objetivo:** aprender a construir una aplicación web moderna utilizando React.

### Temas
- App Router.
- Routing.
- Layouts.
- Pages.
- Dynamic routes.
- Server Components.
- Client Components.
- Rendering.
- SSR.
- SSG.
- Metadata.
- Loading states.
- Error handling.
- Not Found.
- Server-side concepts.
- Caching.
- Optimización.

### 🛠️ Viajia

Construiremos la estructura real:
```text
/                     → Home
/events               → Eventos
/events/[id]          → Detalle
/explore              → Explorar
/profile/[id]         → Perfil
/itinerary            → Itinerario
/messages             → Mensajes
...
```

## 7. Arquitectura Frontend

**Objetivo:** aprender a organizar una aplicación grande sin convertirla en un caos.

### Temas
- Component architecture.
- Feature-based organization.
- Separation of concerns.
- Reusabilidad.
- Composición.
- Services.
- Data layer.
- UI layer.
- Domain concepts.
- Custom hooks.
- Shared components.
- Design system.
- Environment variables.
- Configuración.

## 8. Estado y datos

**Objetivo:** aprender a manejar correctamente los distintos tipos de estado.

### Temas
- Local state.
- UI state.
- Form state.
- URL state.
- Server state.
- Global state.
- Derived state.
- Caching.

### 🛠️ Viajia
- usuario autenticado;
- favoritos;
- seguimiento;
- publicaciones;
- filtros;
- itinerarios;
- notificaciones;
- etc.

## 9. Formularios

### Temas
- Controlled inputs.
- Uncontrolled inputs.
- Validación.
- Errores.
- Formularios complejos.
- React Hook Form.
- Zod.
- Accesibilidad.
- UX de formularios.

### 🛠️ Viajia
- Crear publicación
- Crear itinerario
- Editar perfil
- Buscar eventos
- Filtros
- ...

## 10. Mapas y funcionalidades geográficas

### Temas
- Coordenadas.
- Geolocation API.
- Markers.
- Mapas.
- Rutas.
- Ubicación del usuario.
- Clustering.
- Interacción mapa/lista.

### 🛠️ Viajia

Por ejemplo:
```text
     🗺️
  ● Evento
       ● Evento
             ● Lugar
   ● Hotel
```

## 11. Testing

### Unit testing

#### Vitest
```text
función
 ↓
input
 ↓
resultado esperado
```

### Component / Integration testing
#### React Testing Library
```text
Usuario
 ↓
interacción
 ↓
UI
 ↓
resultado
```

### End-to-End
#### Playwright
```text
Usuario
 ↓
Viajia
 ↓
flujo completo
```

### Temas

mocks;
fixtures;
test doubles;
coverage;
testing strategy;
qué probar;
qué NO probar.

## 12. Accesibilidad
### Temas
- HTML semántico.
- ARIA.
- Keyboard navigation.
- Focus.
- Screen readers.
- Contraste.
- Formularios accesibles.
- Accessible names.
- WCAG.

## 13. Performance
### Temas
- Rendering.
- Re-rendering.
- Bundle size.
- Code splitting.
- Lazy loading.
- Images.
- Fonts.
- Caching.
- Core Web Vitals.
- React performance.
- Next.js optimization.


## 14. Seguridad Frontend

Aunque Viajia no tendrá backend real inicialmente, quiero que tengas fundamentos de:
- XSS.
- CSRF.
- CORS.
- Content Security Policy.
- Secrets.
- Environment variables.
- Dependency security.
- Supply-chain attacks.
- Validación de datos.

## 15. Git, CI/CD y Deployment
### Temas
- Git workflow.
- Branches.
- Commits.
- Merge requests.
- GitLab.
- CI/CD.
- Environment variables.
- Build.
- Production.
- Deployment.

Y eventualmente:
```text
GitLab
   ↓
CI/CD
   ↓
Build
   ↓
Deploy
   ↓
Viajia Web
```

## 16. Portfolio
Finalmente convertiremos todo lo aprendido en algo que puedas mostrar profesionalmente.

Documentaremos:
- arquitectura;
- stack;
- decisiones técnicas;
- testing;
- accesibilidad;
- performance;
- screenshots;
- demo;
- README;
- problemas encontrados;
- soluciones;
- aprendizajes.
