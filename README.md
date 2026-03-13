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

   R: 


### Actividad 2

| Etapa                         |                                                   Descripción                                                      |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------|
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
| Cascada     | Es un modelo muy similar al clasico el cual tambien cuenta con 5 etapas. | Al igual que el modelo clasico, conviene usarlo para sistemas simples |
|             | Su caracteristica principal es que a diferencia del modelo clasico; este | y pequeños, ya que es el modelo menos costoso y el más rapido.        |
|             | aplica una actitud proactiva para identificar todos los problemas y      |                                                                       |
|             | obtener los requerimentos de manera exhaustiva y precisa.                |                                                                       |
|-------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Incremental |                          |                        |
| Prototipos  |                          |                        |
| Espiral     |                          |                        |
| RAD         |                          |                        |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: 
- Justifique su respuesta.

  R:
- ¿Qué etapas principales tendría el desarrollo?

  R:

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [ ] El modelo incremental entrega el sistema en varias versiones.
3. [ ] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [ ] El modelo RAD busca reducir los tiempos de desarrollo.
5. [ ] El modelo en espiral incorpora el análisis de riesgos.
