# Battleship

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación mínimos del proyecto](#5-criterios-de-aceptación-mínimos-del-proyecto)
* [6. Pistas, tips y lecturas complementarias](#5-pistas-tips-y-lecturas-complementarias)
* [7. Hacker edition](#6-hacker-edition)

## 1. Preámbulo

Los videojuegos son una verdadera prueba cuando se trata de tecnología. Uno de
los factores de éxito para el equipo de android, por ejemplo, fue que pudiesen
tener un juego corriendo en los primeros teléfonos. La idea era que si un juego
podía ejecutarse en la plataforma, un programa más simple con pantallas mucho
más fáciles de trabajar que solo tuviese botones y texto debería funcionar aun
mejor.

Entonces la idea de este proyecto es llevar los frameworks de aplicaciones web
al límite de lo que pueden ofrecer, tratar de explorar sus funcionalidades más
avanzadas y lograr un producto que se luzca con tu talento y creatividad
dominando el framework que elijas.

![battleship](https://user-images.githubusercontent.com/7809496/66517403-78ea9680-eab9-11e9-8ab4-8d3c2cc21646.png)

## 2. Resumen del proyecto

Battleship es un juego clásico, con múltiples versiones en juegos de mesa y en
linea (si no lo conoces, puedes verlo en este link :
[battle-ship](https://es.wikipedia.org/wiki/Batalla_naval_(juego))).

El juego es para dos personas. Consiste en que en un tablero cada jugadora coloca
un conjunto de barcos, ocultando su posición del contrincante. Luego, por
turnos, van anunciando una posición del tablero y la enemiga informa si le han
dado a uno de sus barcos o no. El juego termina cuando una jugadora ha conseguido
hundir todos los barcos de la otra.

En este proyecto deberás crear una nueva versión, agregándole algún giro para
actualizarlo y hacerlo más atractivo para las nuevas generaciones. También, no
estás atada a hacer este juego sobre barcos, puedes hacerlo con el tema que más
te guste, siempre y cuando el modo de juego sea parecido.

También el juego debe ser para dos jugadoras, para lograrlo debes pensar en cómo
puedes estructurar la información, estado de la aplicación y cómo guardarlos en
alguna base de datos como __Firebase__ o __MongoDB Stitch__.

### Los objetivos generales de este proyecto son los siguientes

1. Diseñar un esquema de datos y lo apliques a una base de datos conocida,
como _Firebase_ o _MongoDB_.
Muchas veces el como modeles la información es más importante a como estructures
tu código, ya que los problemas que puedan aparecer en el futuro tendrán su
origen acá.

2. No menos importante, tendrás que diseñar y mantener el estado dentro de la
aplicación, esto es la información que usas y guardas temporalmente por cada
ejecución. Para esto unas herramientas para _React_ que te pueden servir son
__Redux__ o también __Context API__ así como también los estados internos de
cada componente. Por el lado de _Angular_ tendrás a los __observables__
y su uso conjunto con los __servicios__ y por supuesto las propiedades que uses
en cada componente.

3. Y finalmente tendrás que diseñar una interfaz llamativa, usando y abusando de
todo lo que sabes de CSS y animaciones para que tengas un juego vistoso y que
guste a la gente. Tienes que invitar a jugar tu juego.

## 3. Objetivos de aprendizaje

Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### HTML

- [ ] **Uso de HTML semántico**

  <details><summary>Links</summary><p>

  * [HTML semántico](https://curriculum.laboratoria.la/es/topics/html/02-html5/02-semantic-html)
  * [Semantics - MDN Web Docs Glossary](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
</p></details>

### CSS

- [ ] **Uso de selectores de CSS**

  <details><summary>Links</summary><p>

  * [Intro a CSS](https://curriculum.laboratoria.la/es/topics/css/01-css/01-intro-css)
  * [CSS Selectors - MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Selectors)
</p></details>

- [ ] **Modelo de caja (box model): borde, margen, padding**

  <details><summary>Links</summary><p>

  * [Box Model & Display](https://curriculum.laboratoria.la/es/topics/css/01-css/02-boxmodel-and-display)
  * [The box model - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  * [Introduction to the CSS box model - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  * [CSS display - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
  * [display - CSS Tricks](https://css-tricks.com/almanac/properties/d/display/)
</p></details>

- [ ] **Uso de flexbox en CSS**

  <details><summary>Links</summary><p>

  * [A Complete Guide to Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  * [Flexbox Froggy](https://flexboxfroggy.com/#es)
  * [Flexbox - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
</p></details>

- [ ] **Uso de CSS Grid Layout**

  <details><summary>Links</summary><p>

  * [A Complete Guide to Grid - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  * [Grids - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
</p></details>

- [ ] **Uso de media queries**

  <details><summary>Links</summary><p>

  * [CSS media queries - MDN](https://developer.mozilla.org/es/docs/CSS/Media_queries)
</p></details>

### JavaScript

- [ ] **Arrays (arreglos)**

  <details><summary>Links</summary><p>

  * [Arreglos](https://curriculum.laboratoria.la/es/topics/javascript/04-arrays)
  * [Array - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/)
  * [Array.prototype.sort() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
  * [Array.prototype.forEach() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
  * [Array.prototype.map() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
  * [Array.prototype.filter() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
  * [Array.prototype.reduce() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
</p></details>

- [ ] **Objetos (key, value)**

  <details><summary>Links</summary><p>

  * [Objetos en JavaScript](https://curriculum.laboratoria.la/es/topics/javascript/05-objects/01-objects)
</p></details>

- [ ] **Diferenciar entre tipos de datos primitivos y no primitivos**

- [ ] **Uso de condicionales (if-else, switch, operador ternario, lógica booleana)**

  <details><summary>Links</summary><p>

  * [Estructuras condicionales y repetitivas](https://curriculum.laboratoria.la/es/topics/javascript/02-flow-control/01-conditionals-and-loops)
  * [Tomando decisiones en tu código — condicionales - MDN](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)
</p></details>

- [ ] **Funciones (params, args, return)**

  <details><summary>Links</summary><p>

  * [Funciones (control de flujo)](https://curriculum.laboratoria.la/es/topics/javascript/02-flow-control/03-functions)
  * [Funciones clásicas](https://curriculum.laboratoria.la/es/topics/javascript/03-functions/01-classic)
  * [Arrow Functions](https://curriculum.laboratoria.la/es/topics/javascript/03-functions/02-arrow)
  * [Funciones — bloques de código reutilizables - MDN](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/Functions)
</p></details>

- [ ] **Pruebas unitarias (unit tests)**

  <details><summary>Links</summary><p>

  * [Empezando con Jest - Documentación oficial](https://jestjs.io/docs/es-ES/getting-started)
</p></details>

- [ ] **Pruebas asíncronas**

  <details><summary>Links</summary><p>

  * [Tests de código asincrónico con Jest - Documentación oficial](https://jestjs.io/docs/es-ES/asynchronous)
</p></details>

- [ ] **Uso de mocks y espías**

  <details><summary>Links</summary><p>

  * [Manual Mocks con Jest - Documentación oficial](https://jestjs.io/docs/es-ES/manual-mocks)
</p></details>

- [ ] **Módulos de ECMAScript (ES Modules)**

  <details><summary>Links</summary><p>

  * [import - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/import)
  * [export - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/export)
</p></details>

- [ ] **Uso de linter (ESLINT)**

- [ ] **Uso de identificadores descriptivos (Nomenclatura y Semántica)**

- [ ] **Diferenciar entre expresiones (expressions) y sentencias (statements)**

- [ ] **Callbacks**

  <details><summary>Links</summary><p>

  * [Función Callback - MDN](https://developer.mozilla.org/es/docs/Glossary/Callback_function)
</p></details>

- [ ] **Promesas**

  <details><summary>Links</summary><p>

  * [Promise - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Promise)
  * [How to Write a JavaScript Promise - freecodecamp (en inglés)](https://www.freecodecamp.org/news/how-to-write-a-javascript-promise-4ed8d44292b8/)
</p></details>

### Control de Versiones (Git y GitHub)

- [ ] **Git: Instalación y configuración**

- [ ] **Git: Control de versiones con git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integración de cambios entre ramas (branch, checkout, fetch, merge, reset, rebase, tag)**

- [ ] **GitHub: Creación de cuenta y repos, configuración de llaves SSH**

- [ ] **GitHub: Despliegue con GitHub Pages**

  <details><summary>Links</summary><p>

  * [Sitio oficial de GitHub Pages](https://pages.github.com/)
</p></details>

- [ ] **GitHub: Colaboración en Github (branches | forks | pull requests | code review | tags)**

- [ ] **GitHub: Organización en Github (projects | issues | labels | milestones | releases)**

### Centrado en el usuario

- [ ] **Diseñar y desarrollar un producto o servicio poniendo a las usuarias en el centro**

### Diseño de producto

- [ ] **Crear prototipos de alta fidelidad que incluyan interacciones**

- [ ] **Seguir los principios básicos de diseño visual**

### Investigación

- [ ] **Planear y ejecutar testeos de usabilidad de prototipos en distintos niveles de fidelidad**

  <details><summary>Links</summary><p>

  * [Intro a testeos usabilidad](https://coda.io/@bootcamp-laboratoria/contenido-ux/test-de-usabilidad-15)
  * [Pruebas con Usuarios 1 — ¿Qué, cuándo y para qué testeamos?](https://eugeniacasabona.medium.com/pruebas-con-usuarios-1-qu%C3%A9-cu%C3%A1ndo-y-para-qu%C3%A9-testeamos-7c3a89b4b5e7)
</p></details>

### Firebase

- [ ] **Firebase Auth**

  <details><summary>Links</summary><p>

  * [Primeros pasos con Firebase Authentication en sitios web - Documentación oficial](https://firebase.google.com/docs/auth/web/start?hl=es)
  * [Administra usuarios en Firebase (onAuthStateChanged)](https://firebase.google.com/docs/auth/web/manage-users?hl=es#get_the_currently_signed-in_user)
</p></details>

- [ ] **Firestore**

  <details><summary>Links</summary><p>

  * [Firestore - Documentación oficial](https://firebase.google.com/docs/firestore?hl=es)
  * [Reglas de seguridad de Firestore - Documentación oficial](https://firebase.google.com/docs/rules?hl=es)
  * [Obtén actualizaciones en tiempo real con Cloud Firestore - Documentación oficial](https://firebase.google.com/docs/firestore/query-data/listen?hl=es)
</p></details>

### MongoDB

- [ ] **Operaciones CRUD (Create-Read-Update-Delete)**

  <details><summary>Links</summary><p>

  * [MongoDB CRUD Operations - Docs (en inglés)](https://docs.mongodb.com/manual/crud/)
  * [Insert Documents - Docs (en inglés)](https://docs.mongodb.com/manual/tutorial/insert-documents/)
  * [Query Documents - Docs (en inglés)](https://docs.mongodb.com/manual/tutorial/query-documents/)
  * [Update Documents - Docs (en inglés)](https://docs.mongodb.com/manual/tutorial/update-documents/)
  * [Delete Documents - Docs (en inglés)](https://docs.mongodb.com/manual/tutorial/remove-documents/)
</p></details>

- [ ] **Modelos y esquemas de datos**

  <details><summary>Links</summary><p>

  * [Schema Validation - Docs (en inglés)](https://docs.mongodb.com/manual/core/schema-validation/)
  * [Data Model Design - Docs (en inglés)](https://docs.mongodb.com/manual/core/data-model-design/)
</p></details>

- [ ] **Respaldo y restauración (backup/restore)**

  <details><summary>Links</summary><p>

  * [MongoDB Backup Methods - Docs (en inglés)](https://docs.mongodb.com/manual/core/backups/)
</p></details>

### Bases de datos

- [ ] **Conexión**

- [ ] **Modelado de datos**

### Angular

- [ ] **Components & templates**

  <details><summary>Links</summary><p>

  * [Angular Components Overview - Documentación oficial (en inglés)](https://angular.io/guide/component-overview)
  * [Introduction to components and templates - Documentación oficial (en inglés)](https://angular.io/guide/architecture-components#introduction-to-components)
</p></details>

- [ ] **Directivas estructurales (ngIf / ngFor)**

  <details><summary>Links</summary><p>

  * [Writing structural directives - Documentación oficial (en inglés)](https://angular.io/guide/structural-directives)
</p></details>

- [ ] **@Input | @Output**

  <details><summary>Links</summary><p>

  * [Component interaction - Documentación oficial (en inglés)](https://angular.io/guide/component-interaction#component-interaction)
</p></details>

- [ ] **Creación y uso de servicios**

  <details><summary>Links</summary><p>

  * [Providing services - Documentación oficial (en inglés)](https://angular.io/guide/architecture-services#providing-services)
</p></details>

- [ ] **Manejo de rutas**

  <details><summary>Links</summary><p>

  * [In-app navigation: routing to views - Documentación oficial (en inglés)](https://angular.io/guide/router)
</p></details>

- [ ] **Creación y uso de Observables.**

  <details><summary>Links</summary><p>

  * [Observables in Angular - Documentación oficial (en inglés)](https://angular.io/guide/observables-in-angular)
</p></details>

- [ ] **Uso de HttpClient**

  <details><summary>Links</summary><p>

  * [Communicating with backend services using HTTP - Documentación oficial (en inglés)](https://angular.io/guide/http)
</p></details>

- [ ] **Estilos de componentes (ngStyle / ngClass)**

  <details><summary>Links</summary><p>

  * [Template syntax - Documentación oficial (en inglés)](https://angular.io/guide/template-syntax#built-in-directives)
</p></details>

### React

- [ ] **JSX**

  <details><summary>Links</summary><p>

  * [Presentando JSX - Documentación oficial](https://es.reactjs.org/docs/introducing-jsx.html)
</p></details>

- [ ] **Componentes y propiedades (props)**

  <details><summary>Links</summary><p>

  * [Componentes y propiedades - Documentación oficial](https://es.reactjs.org/docs/components-and-props.html)
</p></details>

- [ ] **Manejo de eventos**

  <details><summary>Links</summary><p>

  * [Manejando eventos - Documentación oficial](https://es.reactjs.org/docs/handling-events.html)
</p></details>

- [ ] **Listas y keys**

  <details><summary>Links</summary><p>

  * [Listas y keys - Documentación oficial](https://es.reactjs.org/docs/lists-and-keys.html)
</p></details>

- [ ] **Renderizado condicional**

  <details><summary>Links</summary><p>

  * [Renderizado condicional - Documentación oficial](https://es.reactjs.org/docs/conditional-rendering.html)
</p></details>

- [ ] **Elevación de estado**

  <details><summary>Links</summary><p>

  * [Levantando el estado - Documentación oficial](https://es.reactjs.org/docs/lifting-state-up.html)
</p></details>

- [ ] **Hooks**

  <details><summary>Links</summary><p>

  * [Presentando Hooks - Documentación oficial](https://es.reactjs.org/docs/hooks-intro.html)
</p></details>

- [ ] **CSS modules**

  <details><summary>Links</summary><p>

  * [Adding a CSS Modules Stylesheet - Documentación de Create React App (en inglés)](https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/)
</p></details>

- [ ] **React Router**

  <details><summary>Links</summary><p>

  * [Quick Start - Documentación oficial (en inglés)](https://reactrouter.com/web/guides/quick-start)
</p></details>

### Vue

- [ ] **Instancia de Vue.js**

  <details><summary>Links</summary><p>

  * [La instancia Vue - Documentación oficial](https://es.vuejs.org/v2/guide/instance.html)
</p></details>

- [ ] **Datos y métodos**

  <details><summary>Links</summary><p>

  * [Datos y Métodos - Documentación oficial](https://es.vuejs.org/v2/guide/instance.html#Datos-y-Metodos)
</p></details>

- [ ] **Uso y creación de componentes**

  <details><summary>Links</summary><p>

  * [Conceptos Básicos de Componentes - Documentación oficial](https://es.vuejs.org/v2/guide/components.html)
</p></details>

- [ ] **Props**

  <details><summary>Links</summary><p>

  * [Pasando datos a componentes secundarios con Props - Documentación oficial](https://es.vuejs.org/v2/guide/components.html#Pasando-datos-a-componentes-secundarios-con-Props)
</p></details>

- [ ] **Directivas (v-bind | v-model)**

  <details><summary>Links</summary><p>

  * [v-bind - Documentación oficial](https://es.vuejs.org/v2/api/#v-bind)
  * [Binding en Formularios - Documentación oficial](https://es.vuejs.org/v2/guide/forms.html)
</p></details>

- [ ] **Iteración (v-for)**

  <details><summary>Links</summary><p>

  * [Mapeando una matriz a elementos con v-for - Documentación oficial](https://es.vuejs.org/v2/guide/list.html#Mapeando-una-matriz-a-elementos-con-v-for)
</p></details>

- [ ] **Eventos (v-on)**

  <details><summary>Links</summary><p>

  * [Manejo de eventos - Documentación oficial](https://es.vuejs.org/v2/guide/events.html)
</p></details>

- [ ] **Propiedades Computadas y Observadores**

  <details><summary>Links</summary><p>

  * [Propiedades Computadas y Observadores](https://es.vuejs.org/v2/guide/computed.html)
</p></details>

- [ ] **Routing**

  <details><summary>Links</summary><p>

  * [Getting Started - Documentación oficial de Vue Router](https://router.vuejs.org/guide/#html)
</p></details>

- [ ] **Clases y Estilos**

  <details><summary>Links</summary><p>

  * [Enlace Clases y Estilos - Documentación oficial](https://es.vuejs.org/v2/guide/class-and-style.html)
</p></details>

## 4. Consideraciones generales

Este proyecto se debe resolver en equipos de 3 personas.

La planificación es clave, por lo que debes coordinarte con tu equipo e
identificar las historias de usuaria, priorizarlas y trabajarlas sprint a sprint
cuidando de que hayan test para el código, se haya hecho test con usuarios sobre
la usabilidad y cumpliendo con las ceremonias de SCRUM que has aprendido a lo
largo del bootcamp.

También para este proyecto, usa cualquier framework (_React_, _Angular_, etc...)
cuidando de que se vea bien en las pantallas de celular o computador, que las
jugadoras puedan elegir la plataforma libremente sin prejuicio de la
jugabilidad. Para esto considera un tamaño variable de pantalla y que los
elementos del juego se redimensionen dependiendo de ella.

Para la base de datos, trata de modelar bien cómo guardarás los datos y piensa
bien el cómo soportar varios usuarios a la vez en diferentes salas de juego.
Recuerda que "battleship" se juega de a dos. Usa tu creatividad para asignar
contrincantes a cada jugadora.

### Definición de terminado para cada historia de usuaria

* Debes haber recibido _code review_ de al menos una compañera.
* Haces _test_ unitarios y, además, has testeado tu producto manualmente.
* Hiciste _tests_ de usabilidad e incorporaste el _feedback_ del usuario.
* Desplegaste tu aplicación y has etiquetado tu versión (git tag).

## 5. Criterios de aceptación mínimos del proyecto

### Definición del producto

La [_Product Owner_](https://youtu.be/r2hU7MVIzxs) nos presenta este _backlog_
que es el resultado de su trabajo colaborativo.

***

### Historias de usuaria

#### [Historia de usuaria 1] Crear usuaria e iniciar sesión

Yo como usuaria debo poder crear una cuenta y
autenticarme usando el login de Google para acceder al juego.

#### [Historia de usuaria 2] Crear o unirme un juego

Yo como usuaria debería poder crear un nuevo juego o
unirme a un juego creado por otra usuaria.

#### [Historia de usuaria 3] Desplegar mi flota

Yo como usuaria quiero posicionar mis naves en una tabla (grilla)
y avisar cuando estoy lista para comenzar a jugar.

#### [Historia de usuaria 3] Atacar y conocer el resultado

Yo como usuaria debería saber cuando es mi turno para escoger
una coordenada a atacar. Deberia además poder saber si anchunté o no
alguna nave de mi oponente y si hundí o no alguna de sus naves.

#### [Historia de usuaria 4] Recibir ataques

Yo como usuaria debería saber cual coordenada ha atacado mi oponente
y saber si anchuntó o no alguna de mis naves y si hundió alguna o no.

#### [Historia de usuaria 5] Conocer el estado del juego

Yo como usuaria debería poder conocer el estado del juego, ver un historial
de los movimientos jugados y cuales dieron en el blanco y cuales no, y si
he hundido una nave oponente o no, además de ver mis naves hundidas y
coordenadas atacadas.

#### [Historia de usuaria 6] Fin de un juego

Yo como usuaria debería poder saber cuando se ha terminado el juego
y quien es la persona ganadora, además de poder abandonar un juego si
es necesario.

***

#### Criterios de aceptación

Lo que debe ocurrir para que se satisfagan los objetivos del proyecto
y cubra las necesidades de las usuarias.

* Crear cuenta y/o iniciar sesión con Google.
* Crear o unirse a un juego.
* Escoger las coordenadas de posiciones de naves antes de empezar el juego.
* Iniciar el juego, escoger una coordenada para atacar las naves de mi
oponente y saber el resultado de ese ataque
(da en el blanco, hunde una nave, o falla).
* Saber el estado del juego: A quien le toca; Historial de movimientos,
tiros al blanco o al agua y quien resulta vencedora.
* Se ve y funciona bien en un dispositivo móvil.

## 6. Pistas, tips y lecturas complementarias

1. Modelar los datos, es un paso muy importante, considera que el juego es de
dos personas, pero más de una pareja puede estar jugando a la vez (modelo de
salón de juego).

2. Haz un _fork_ de este repositorio (en GitHub). Luego que tus compañeras de
proyecto hagan a su vez _fork_ de __tu__ repositorio. Recuerda, como en
proyectos anteriores, que una de ustedes debe ser la integradora o _maestra_ del
repositorio principal.

3. Para facilidad piensa en una cuadrícula y que cada _barco_ solo ocupa una de
ellas. Si quieres escalar en dificultad para este proyecto, puedes intentar con
barcos de formas y tamaños diferentes.

4. Ten el concepto de turno y guarda de quién es el turno cada vez en la base de
datos. También define la condición de término en una forma que tu código lo
pueda detectar, como por ejemplo: todos los barcos se han hundido.

5. Llevar el estado del juego es primordial, define bien las acciones,
reducidores y datos que estarán en cada juego, turno y movida de los jugadores.
Puedes hacer un diagrama de estados para esto:
[diagrama-estados](https://www.lucidchart.com/pages/es/diagrama-de-maquina-de-estados)

### Otros recursos

#### Bibliotecas y componentes

* [redux](https://es.redux.js.org/)
* [animaciones-react](https://medium.com/@dmitrynozhenko/5-ways-to-animate-a-reactjs-app-in-2019-56eb9af6e3bf)
* [animaciones-angular](https://blog.angularindepth.com/total-guide-to-dynamic-angular-animations-that-can-be-toggled-at-runtime-be5bb6778a0a)
* [servicios-angular](https://angular.io/tutorial/toh-pt4)
* [contexto-react](https://es.reactjs.org/docs/context.html)
* [hooks-react](https://es.reactjs.org/docs/hooks-intro.html)
* [Más animaciones para frameworks](https://popmotion.io/pose/)

#### Conceptos

* [observables](https://angular.io/guide/observables)
* [visualizador-observables](https://rxviz.com/)
* [visualizador-observables-2](https://rxmarbles.com/)

## 7. Hacker edition

Hasta el momento has usado javascript, html, css, react, angular, y otras
herramientas para hacer tus aplicaciones, pero ¿qué tal si te aventuras con tu
grupo a hacer este proyecto usando algún framework orientado a videojuegos?. Te
invitamos a aceptar el desafío e intentar hacer el juego usando algún
__game engine__ como los que están a continuación o el que tu encuentres en la
internet:

* [GDevelop](https://gdevelop-app.com/)
* [Moddio](https://www.modd.io/)
* [Construct](https://www.scirra.com)
* [Babylon](https://www.babylonjs.com/)
* [Impact](https://github.com/phoboslab/impact)
* [Phaser](https://phaser.io)
