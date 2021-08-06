---
layout: post
title:  "Welcome to the iOS Course!"
date:   2021-08-06 14:08:55 -0500
categories: index
---
In this course you will be learning the skills to be an ios developer, if you follow this index you will be in a path from  to jr  to semi senior and senior.

# Index
## iOS JR

### 1. Común 
  * #### Conceptos POO
    - Solid
      * Single responsability
      * Open Closed
      * Liskov substitution
      * Dependency inversion 
    - Pilares Programación orientada a Objetos 
      * Encapsulamiento 
      * Herencia
      * Polimorfismo
      * Abstracción
    - Paradigmas de programación distintos a orientados a objetos
      * Estructurada
      * Funcional
    - Patrones de diseño

### 2. Conocimientos de creación de Interfaces visuales 
  * Creación de vistas usando storyboards
  * Creación de vistas usando XIBs
  * Conexión de elementos visuales desde Storyboards / XIBs hacía clases UIViewController / UIView
  * Autolayout (básico)  

### 3. Composición de elementos de UI de una aplicación iOS
  * UIViewController
    - Ciclo de vida
    - Implementación en  interface builder y código
  * UINavigationController
    - Navegación de controladores
    - Implementación en interface builder y código  
  * UITabBarController
    - Navegación de controladores
    - Implementación en interface builder y código
  * UITableViewController
    - Implementación en interface builder y código
  * UIView
    - Implementación y uso de los componentes básicos (UIButton, UILabel, UIImageView, etc.)
  * Acceso de recursos a través de red
    - Conexión a web services utilizando el SDK de iOS  Uso de Codable y URL Session
  * Xcode
    - Creación de proyectos (iOS)
    - Compilación, ejecución y debugging (básico)
    - Navegación dentro de un proyecto iOS
  * Conocimientos de Core Data (básico)
  * GIT

## Extras iOS JR

#### 1. Mejora en el dominio de la creación de interfaces visuales, creación e implementación de vistas complejas y animaciones sencillas.

#### 2. Separación de conceptos, manejo apropiado de la clase UIViewController, delimitación del alcance de interés del código en UIViewController
  * Uso avanzado de UIViewController, incluyendo su uso dentro de elementos de navegación (UINavigationController y UITabBarController)
  * Modificación de los aspectos visuales de estos componentes a través del interface builder o código

#### 3. Mejor comprensión del consumo de servicios web y conexión de aplicaciones iOS a la red
  * Potencialmente, uso de librerías de conexiones a redes más comunes en proyecto iOS, sin caer en la profundidad técnica y configuraciones avanzadas de dichas librerías

#### 4. Buen manejo de elementos visuales, incluyendo buenas prácticas
  * Creación de vistas personalizadas utilizando UIView
  * Mejor comprensión del funcionamiento de Autolayout y el concepto de intrinsic content size utilizado en vistas de uso común como UILabel, UIButton, UITextField
  * Uso intermedio de los métodos disponible en UIKit para animación de UIView (UIView Animations)

#### 5. Conocimiento de frameworks en el SDK de iOS
  * MapKit
  * Uso intermedio de algunos elementos de UIKit
    - UITableView
    - UICollectionView
  * Nociones de codificación orientada a obtener el mejor desempeño posible de la aplicación en los dispositivos
  * Uso de librerías gestoras de dependencias populares en iOS (Cocoapods, Carthage) sin caer en la profundidad técnica
 
## iOS Semi Senior

#### 1. Uso intermedio de algunos elementos de UIKit
  * UITableView / UICollectionView
    - Auto-redimensionado de celdas
    - Personalización de celdas
    - Implementación en interface builder y código
  * Animacion de UIView
  * View Controller Containment

#### 2. Conocimiento de frameworks comunes del API iOS
  * CoreData
  * MapKit
  * WebKit
  * TextKit
  * CoreLocation
  * CoreAnimation

#### 3. Uso correcto de UIViewController y su función dentro de otras arquitecturas como MVP, MVVM, VIPER o CLEAN
  * Conocimiento técnico del por qué es necesario saber esto

#### 4. Nociones de mejora de desempeño del código que conforma un proyecto
  * Sanitización del main thread y comprensión técnica del por qué es esto requerido

#### 5. Uso de librerías gestoras de dependencias populares en iOS (Cocoapods / Carthage)

#### 6. Separación de conceptos en clases AKA SOLID concept

#### 7. Conocimiento intermedio de las características de lenguajes de programación utilizados por iOS
  * Swift
    - Modificadores de acceso
    - Class vs struct vs enum
    - Interoperabilidad con Objective-C
    - NoticationCenter
    - Associated types
    - Collections
    - Closures y functions
    - POP
    - Result type
    - Raw strings
    - String interpolation
  * Objective-C
    - Características de una declaración @property
    - Instancetype vs id
    - Operación del lenguaje en tiempo de ejecución (dinámico)
    - Interoperabilidad con Swift
  * Gestión de uso de memoria
    - Manejo de memoria y su impacto
    - ARC
    - Ownership qualifiers
      * Objc: autoreleasing, strong, unsafe_unretained, weak
      * Swift: strong, weak or unowned
    - Retain cycles
    - Heap vs Stack
  * Gestión de tareas mediante hilos
    - Uso de Grand Central Dispatch
    - Uso de Operations
    - Uso de closures para la ejecución de tareas en diferentes hilos
  * Unit Testing (básico)
  * Layout en código
    - Uso de anchors y otras técnicas
  * Security
    - Keychain y otros métodos


## Extras iOS Semi Senior

#### 1. Mejor dominio de los frameworks contenidos en el SDK de iOS, incluyendo pero no limitando
  * CoreData
  * MapKit
  * WebKit
  * UIKit

#### 2. Comprensión del funcionamiento de los patrones de diseño y qué solucionan
  * Capacidad de reconocerlos sin conocer completamente la forma
#### 3. Codificación orientada a performance y reutilización del código

#### 4. Correcto uso de los recursos del sistema operativo:
  * Energía
  * Red
  * Memoria

#### 5. Conocimiento avanzado de creación de interfaces visuales tanto en código como en interface builder, incluyendo:
  * Autolayout
  * Animación de vistas
  * Transición de UIViewController
  * Size classes

#### 6. Workspace, project, schemes, targets, firma de aplicaciones, certificados, provisionings
  * Conocimiento del mecanismo de firma de aplicacion iOS.


## iOS Senior
#### 1. Conocimiento avanzado de creación de interfaces visuales incluyendo:
  * Autolayout
  * Animación
  * Transición
  * Size classes
  * Vistas custom reusables

#### 2. Sólido conocimiento en programación concurrente
  * Grand Central Dispatch
  * Operations

#### 3. Sólido conocimiento del lenguaje de programación Swift
  * First-Class Functions
  * Generics
  * Collections
  * Iterators and Sequences

#### 4. Sólido conocimiento de los frameworks incluidos en el SDK de iOS, capacidad de implementar o incluir estos en algún proyecto de acuerdo a las requerimientos del mismo

#### 1. Herramientas gestoras de dependencias
* Ventajas y desventajas de su uso

#### 5. Sólido conocimiento de paradigmas de programación, incluyendo pero no limitando:
  * Orientada a objetos
  * Reactiva
  * Orientada a protocolos
  * Funcional

#### 6. Setup y configuración de ambientes CI/CD para mobile

#### 7. Advanced Unit testing (Mock, Stub)
  * Pruebas de integración
  * TDD
  * FIRST 

#### 8. Debugging y breakpoints, condiciones y lenguaje

#### 9. Creación de frameworks / librerías como parte de separación de conceptos

#### 10. Codificación orientada a performance y/o reusabilidad

#### 11. Comprensión y aplicación de patrones de diseño

#### 12. Introducción de patrones arquitectónicos (no se espera el mismo nivel que un Software Designer o un Architect)

#### 13. App distribution (Fastlane, AppCenter, Store, Testflight)

#### 14. Advanced Project Configuration.

## Extras iOS Senior

#### 1. Dominio en la creación de interfaces complejas

#### 2. Dominio del proceso de creación de aplicaciones end to end

#### 3. Dominio del proceso de debugging para la solución de problemas simples o complejos

#### 4. Conocimiento sólido de los lenguajes de programación Objective-C y Swift

#### 5. Conocimientos sólidos de buenas prácticas para su aplicación en proyectos complejos

#### 6. Generación de frameworks o librerías personalizadas para el uso compartido en proyectos

#### 7. Enfoque a la optimización del tiempo en el proceso de desarrollo mediante el uso de herramientas como: Fastlane, CI/CD, code repositories, etc. (no se requiere un conocimiento avanzado)

#### 8. Generación de binarios para su distribución: AdHoc, Enterprise, Testflight, Store, etc.
