# Investigacion React

---
1. **¿Que es React.js?**
* React.js, o simplemente React, es una biblioteca de JavaScript de código abierto utilizada para construir interfaces de usuario (UI) interactivas y reutilizables.
Fue desarrollado por Facebook y se utiliza comúnmente en el desarrollo de aplicaciones de una sola página (SPA) donde las actualizaciones de la interfaz de usuario son frecuentes. React permite a los desarrolladores crear componentes de interfaz de usuario independientes que gestionan su propio estado y se pueden combinar para construir interfaces complejas.


---
2. **¿Cuáles son las diferencias entre React.js versión 18?**

* **Routing**
    * React.js en sí mismo no proporciona enrutamiento, pero hay bibliotecas externas como React Router que pueden utilizarse para gestionar la navegación en una aplicación.
* **Rendering**
    *  La versión 18 de React introduce un nuevo modelo de representación denominado "Concurrent Rendering". Este modelo mejora la concurrencia en la actualización de la interfaz de usuario, haciendo que la aplicación sea más receptiva.
* **Data Fetching**
    * React 18 incluye características mejoradas para la búsqueda y obtención de datos, como la API de Suspense. Esto ayuda a manejar de manera más efectiva la carga de datos asíncronos.
* **Styling**
    *  React no incluye por defecto un sistema de estilos, pero se pueden usar diferentes enfoques como CSS, preprocesadores como Sass, o bibliotecas como Styled Components. Las mejoras en la versión 18 pueden incluir optimizaciones en el manejo de estilos.
* **Optimizations**
    * React 18 se centra en mejorar el rendimiento y la optimización de la representación, haciendo que la actualización de la interfaz de usuario sea más eficiente y rápida.
* **Typescript**
    * React es compatible con TypeScript, un superset de JavaScript que agrega tipado estático al lenguaje. Esta compatibilidad permite una mejor gestión de los tipos de datos en una aplicación React.
---
3. **Define los siguientes conceptos detrás de React:**
* **components**
    * Los componentes en React son bloques de construcción reutilizables que encapsulan la lógica y la interfaz de usuario de una parte específica de la aplicación. Pueden ser funcionales o basados en clases.
* **JSX**
    * JSX (JavaScript XML) es una extensión de sintaxis de JavaScript que permite escribir código HTML dentro de archivos JavaScript. JSX facilita la creación y estructuración de componentes en React de una manera más declarativa.
* **props**
    * Las "props" (abreviatura de propiedades) son objetos que contienen información que puede ser pasada de un componente principal a sus componentes hijos. Son la forma principal de pasar datos entre componentes en React.
* **state**
    * El "state" representa la información interna de un componente que puede cambiar a lo largo del tiempo debido a interacciones del usuario, eventos, o cambios en la aplicación. El estado permite que los componentes React se actualicen y respondan a cambios.

---
4. **Investiga sobre el patrón de diseño estructural llamado Composite, en qué consiste y
cuál es su relación con React?**

* El patrón de diseño estructural llamado Composite se utiliza para componer objetos en estructuras de árbol para representar jerarquías de parte-todo. Permite a los clientes tratar tanto a los objetos individuales como a las composiciones de objetos de manera uniforme. En el contexto de React, este patrón se relaciona con la creación y composición de componentes.

* En React, los componentes pueden ser considerados como nodos en un árbol de jerarquía. Pueden contener otros componentes más pequeños, y estos a su vez pueden contener más componentes. Al construir aplicaciones en React, se sigue un enfoque jerárquico y de composición de componentes, lo que se alinea con los principios del patrón Composite. Esto permite construir interfaces de usuario complejas dividiéndolas en componentes más pequeños y reutilizables.

---
5. **Investiga sobre el patrón de diseño estructural llamado State, en qué consiste y cuál es
su relación con React?**

* El patrón de diseño estructural llamado State se refiere a la gestión del estado interno de un objeto y cómo este estado afecta su comportamiento. En el contexto de React, el estado se refiere a la información interna de un componente que puede cambiar a lo largo del tiempo.

* React utiliza el concepto de estado para manejar la información dinámica en un componente. Los componentes pueden tener un estado interno que se puede modificar en respuesta a eventos, interacciones del usuario o cambios en la aplicación. Cuando el estado de un componente cambia, React se encarga de volver a renderizar el componente para reflejar esos cambios en la interfaz de usuario.

* El uso eficaz del estado en React permite crear componentes dinámicos e interactivos. Los cambios en el estado desencadenan actualizaciones automáticas en la interfaz de usuario, proporcionando una experiencia de usuario más dinámica y receptiva.
---

## Ir a Tres en linea

[Ir a tres en linea](tres-en-linea.md)
