# ANGULAR

framework de JavaScript de código abierto que se utiliza para construir aplicaciones web y móviles. Fue desarrollado por Google y se utiliza ampliamente para crear aplicaciones de una sola página (Single-Page Applications o SPAs) y aplicaciones móviles híbridas. Angular utiliza una arquitectura basada en componentes y ofrece muchas características y herramientas para facilitar el desarrollo de aplicaciones, como enrutamiento, gestión de formularios, inyección de dependencias, animaciones, pruebas unitarias, entre otras. Además, Angular cuenta con una gran comunidad de desarrolladores y una amplia documentación disponible.

### ARQUITECTURA DE ANGULAR

La arquitectura de Angular se basa en el patrón de arquitectura Model-View-Controller (MVC).

1.- Componentes: Los componentes son bloques de construcción fundamentales de una aplicación Angular. Representan diferentes partes de la interfaz de usuario, como encabezados, menús, secciones de contenido, etc.

2.- Servicios: Los servicios son clases que proporcionan funcionalidad compartida y se pueden inyectar en cualquier componente o servicio que los necesite.

3.- Directivas: Las directivas son atributos personalizados que se utilizan para agregar comportamiento a elementos HTML existentes o para crear nuevos elementos personalizados.

4.- Pipes: Los pipes se utilizan para transformar el valor de una propiedad antes de mostrarlo en la interfaz de usuario.

5.- Módulos: Los módulos se utilizan para organizar los componentes, servicios y otros artefactos de una aplicación en bloques funcionales.

### RxJS

- Es parte del proyecto ReactiveX(Colección de proyectos de código abierto que incluye RxJava, RxJS, RxSwift, Rx.NET y otros)
  -Es una biblioteca para programación reactiva usando Observables.
- Es una forma de escribir programas asincronos basado en eventos mediante secuencia de Observables.
  -Proporciona un conjunto de operadores que se puede utilizar para transformar filtrar y convinar observables. Estos operadores puede utilizarce para crear flujo de datos.

# Observable

- es un objeyo que contiene un método subscrite, el cual tiene como parametro un observer y devuelve un objeto suscription.

# Observer

- es un objeto que contiene 3 métodos next(), error() y complete().
- se suscribe a un observable y cada vez que este emite un valor se ejecuta el metodo next() y cuando finaliza las emisiones llaman al método complete(). En caso de error al método error().

# Subscription

- objeto que tiene un método unsubscription().
- es el que mantiene la relación entre el observer y el observable.
- El método unsubscription() se ejecuta para finalizar una relación, haciendo que el observer dejaria de recibir los valores emitidos.

### DIRECTIVAS

- son clases que añaden un nuevo comportamiento o modifican los elementos del DOM.
- Extienden las funcionalidades del HTML.

# Tipos de directivas

- Directivas de componentes.
- Directivas estructurales.
- Directivas de atributos.

### Directivas de componentes

- Son directivas con un template y tienen decoradores @component.
- Los componentes son un tipo de directivas que tienen un template y se utiliza para construir la interfaces de usuario.

### Directivas estructurales

- Se utiliza para cambiar el diseño del DOM, añadiendo y eliminando elementos del DOM.
- Todas las directivas estructurales están precedidas por el símbolo Asterix (\*).
  Ejemplo:
  -> ngIf, ngFor, ngSwitch

### Directivas de atributos

- Se utiliza para cambiar la apariencia o el comportamiento de un elemento.
  Ejomplo:
  -> ngStyle, ngClass, ngModel
