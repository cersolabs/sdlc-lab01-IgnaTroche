[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Porque previamente se debe cumplir una serie de pasos previa en un orden especifico y cumplir ciertas pautas para asegurar el exito del proyecto y la calidad del software que entreguemos.

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: Significa que para el desarrollo del proyecto, utilizaremos un plan el cual nos guiara durante el desarrollo y pautara la forma de proceder mediante etapas sucesivas hasta que se finalize el proyecto y el software este completamente funcional.

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: Las ventajas de utilizar un plan son:
        - Nos permite presupuestar los costos del proyecto y estimar los tiempos de desarrollo requerido con facilidad.
        - El desarrollo se vuelve predecible gracias a las etapas sucesivas definidas al inicio del proyecto.
        - Los requisitos planteados y acordados con el cliente al principio del proyecto seran los que se vean reflejados en la versión final del software.

5. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: Las críticas que reciben estos modelos son:
        - Hoy en día rara vez los proyectos son tan lineales.
        - En estos, hay muy poca interacción con el cliente.
        - Los errores u omisiones que se cometen en una etapa previa, se arrastran facilmente a etapas posteriores.
        - Los requerimentos deben obtenerse al inicio del proyecto y no pueden ser cambiados con posterioridad.
        - Son dificiles de aplicar a proyectos grandes o complejos.

7. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: Las organizaciones combinan ambos enfoques porque así logran planificación y control del proyecto, pero también flexibilidad para adaptarse a cambios y mejorar el            software durante el desarrollo.


### Actividad 2

|            Etapa              |                                                   Descripción                                                      |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|
|                               | Es un relevamiento que realizan los analistas de la organización para identificar sus necesidades y los problemas  |
|           Análisis            | que deben abordarse con un sistema informatico. El resultado de este proceso es la elaboración de un documento que |
|                               | siguiendo ciertas reglas y convenciones especificas, capture todos los requerimentos de los usuarios. Tambien con  |
|                               | este proceso, se deben identificar las restricciones y limitaciones que puedan haber.                              |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|
|                               | Se realiza un diseño del sistema informatico que abordara los problemas identificados teniendo en cuenta los       |
|            Diseño             | requerimentos obtenidos en la etapa anterior y las restricciones establecidas. Con este proceso se realiza una     |
|                               | documentación detallada y técnica que le permita a los programadores construir el sistema de manera efectiva.      |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|
|         Codificación          | Los programadores comienzan a codificar el sistema siguiendo las especificaciones del diseño, donde construyen el  |
|                               | codigo del software usando un lenguaje de programación determinado.                                                |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|
|            Prueba             | Esta etapa se encarga de identificar los posibles errores del sistema antes de lanzarlo, con el objetivo de        |
|                               | reportarlos y corregirlos.                                                                                         |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|
| Puesta en marcha / Despliegue | En esta etapa ya se realiza la instalación del sistema en las computadoras del cliente y se les da capacitación a  |
|                               | los usuarios para que puedan utilizar eficientemente el nuevo software.                                            |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------|

* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
    
    R: Los requerimientos del sistema los capturamos en la etapa de Análisis, es decir en la primer etapa.
    
  * ¿En qué etapa se construye el programa?

    R: El programa se construye durante la etapa de Codificación, la tercer etapa.
    
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R: El objetivo de las pruebas es poder guiar de una manera mas eficiente todo el proyecto para que sea exitoso.
  
### Actividad 3
Ordene las siguientes etapas según corresponda al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R: 1 - Ingeniería de requerimientos
   2 - Diseño
   3 - Codificación
   4 - Prueba
   5 - Despliegue

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: Que este error se arraste con facilidad a las etapas siguientes, requiriendo hacer toda una reforma completa en el plan de desarrollo luego.
    
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R: Porque no esta planeado para tener que cambiar estos mismos, al hacerlo, significaria un aumento en los costos y tiempo del desarrollo.
    
### Actividad 4
Complete la siguiente tabla.
| Modelo      |                         Característica principal                         |                        Cuándo conviene usarlo                         |
| ----------- |--------------------------------------------------------------------------| ----------------------------------------------------------------------|
| Cascada     | Es un modelo el cual cuenta con 5 etapas de desarrollo, muy similar al   | Conviene usarlo para sistemas simples y pequeños, los cuales tengan   |
|             | modelo clasico. Las etapas se realizan una despues de la otra, no se     | bien definidos sus requisitos desde el inicio y no se esperen         |
|             | pasa a la siguiente hasta terminar la anterior.                          | cambios.                                                              |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Incremental | Es un modelo secuencial en el cual se desarrolla y se entrega el sistema | Conviene usarlo cuando el cliente necesite el sistema con urgencia y  |
|             | en varias versiones cada una con más funcionalidades que la anterior     | se disponga de poco tiempo para desarrollarlo por completo.           |
|             | según se requiera en base a los requerimentos que surjan en el camino.   |                                                                       |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Prototipos  | Es un modelo en el cual se crea un prototipo del sistema con el fin de   | Cuando en el proyecto solicitado se tengan dificultades para aclarar  |
|             | aclarar requerimentos con el cliente para luego proceder a desarrollar   | los requerimentos o que el cliente tenga dudas de como se vera y      |
|             | software.                                                                | necesite obtener una vista previa del sistema.                        |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Espiral     | Combina el estilo de desarrollo del modelo incremental pero agregando a  | Cuando el proyecto es grande,complejo o tiene muchos riesgos.         |
|             | cada etapa un análisis de riesgo a partir del cual el modelo puede ser   |                                                                       |
|             | modificado, restringido, puesto en pausa o, inclusive, abortado.         |                                                                       |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|
| RAD         | Permite desarrollar aplicaciones muy rápidamente usando herramientas     | Cuando se necesite desarrollar un sistema complejo en poco tiempo y   |
|             | automáticas, componentes reutilizables y equipos trabajando en paralelo. | se pueda dividir el desarrollo en equipos que trabajen en paralelo.   |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
    R: El modelo más adecuado es el espiral, el cual integra un análisis de riesgo en todas sus etapas para asegurar que durante el desarrollo no haya problemas y
       no se arrastren errores.
    
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
    El modelo mas efectivo en este caso seria el de prototipos, ya que se van creando versiones minimalistas y funcionales del sistema para poder aclarar y comprender
    de una manera más precisa los requerimentos del usuario.
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: El modelo de desarrollo mas adecuado para este proyecto sería el modelo de Cascada
  
- Justifique su respuesta.

  R: Recomiendo el modelo de cascada ya que es el mas optimo para proyectos pequeños como el propuesto, ya que es el menos costoso, el de desarrollo más rapido y el más practico para capturar las necesidades del cliente.
  
- ¿Qué etapas principales tendría el desarrollo?

  R: El desarrollo iniciaria con la etapa de ingeniería de requerimientos, en la cual entrevistarenos a los empleados del comercio para conocer sus necesidades y requerimientos del sistema.
  Una vez capturemos todos los requerimientos del sistema, empezariamos con la etapa de diseño, en la qué vamos realizar el diseño del sistema, el cual servirá de guía para la próxima etapa.
  La tercer etapa sería la de codificación, en la cual se empezara a programar el sistema, usando de guía el diseño hecho en la anterior etapa.
  Una vez terminada la codificación, se realiza la etapa de prueba, para buscar posibles errores en el sistema y así poder arreglarlos.
  Por ultimo, se realiza la etapa de lanzamiento, en la cual instalamos el sistema en todas los equipos del cliente y les damos capacitación a los empleados para que puedan usar eficientemente el nuevo sistema.

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [X] El modelo incremental entrega el sistema en varias versiones.
3. [X] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [X] El modelo RAD busca reducir los tiempos de desarrollo.
5. [X] El modelo en espiral incorpora el análisis de riesgos.
