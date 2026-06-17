Propuesta de Prompt para la Evaluación del Taller 7

Programación Orientada a Objetos

Carrera: Ciencias de la Computación
Universidad: Universidad Técnica Particular de Loja (UTPL)

⸻

Objetivo

Analizar, validar, retroalimentar y evaluar las soluciones entregadas por los estudiantes para el Taller 7, considerando tanto el modelado UML como la implementación en Java, aplicando criterios de calidad de software, Programación Orientada a Objetos, UML, herencia y buenas prácticas de desarrollo.

⸻

Instrucciones Generales

1. Enunciado de referencia

Utiliza como referencia el repositorio oficial:

https://github.com/POO-UTPL/APEB1_Taller7

Si el repositorio no se encuentra disponible, utiliza el archivo README.md adjunto.

⸻

2. Archivos de entrada

Modelado UML

Cada ejercicio incluye:

* Archivo .png
* Archivo .dia (opcional)

Implementación Java

* Archivos .java
* Proyecto completo del estudiante

⸻

3. Extracción del UML

A partir de la imagen UML proporcionada:

1. Identifica:
    * Clases
    * Atributos
    * Métodos
    * Relaciones
    * Jerarquías de herencia
2. Genera exclusivamente el diagrama en formato Mermaid.

Formato requerido

classDiagram
class NombreClase1{
  -tipo1 atributo1
  +tipo2 atributo2
  +metodo1(tipo parametro) tipoRetorno
  -metodo2() tipoRetorno
}
NombreClase2 --|> NombreClase1
NombreClase3 ..> NombreClase1 : usa

Restricción

No incluir:

* Explicaciones
* Comentarios
* Texto adicional

Únicamente el código Mermaid.

⸻

4. Generación de Soluciones Ideales

4.1 Solución UML Ideal

Generar una versión mejorada del modelado UML considerando:

Programación Orientada a Objetos

* Abstracción
* Encapsulamiento
* Herencia
* Relaciones UML adecuadas

Calidad de Diseño

* Principios SOLID
* Buenas prácticas de modelado
* Cohesión
* Bajo acoplamiento
* Claridad conceptual

UML

* Relaciones correctas
* Multiplicidades apropiadas
* Jerarquías coherentes

⸻

4.2 Solución Java Ideal

Generar una versión optimizada del código Java considerando:

POO

* Abstracción
* Encapsulamiento
* Herencia
* Uso correcto de constructores

Calidad de Software

* Principios SOLID
* Código limpio
* Legibilidad
* Modularidad

Arquitectura

* Patrón MVC
* Entradas y salidas únicamente en main()

Estructuras de Control

* Selectivas
* Repetitivas

Estructuras de Datos

* Arreglos estáticos
* Arreglos dinámicos
* ArrayList
* Colecciones

⸻

5. Contenidos Evaluados

Unidad 1. Conceptos Principales de POO

* Introducción al paradigma orientado a objetos
* UML
* Abstracción
* Encapsulamiento
* Herencia
* Polimorfismo
* Clases y objetos

⸻

Unidad 2. Estructura y Creación de Programas

* Declaración de clases
* Métodos
* Objetos
* Métodos establecer y obtener
* Constructores
* Asociación
* Agregación
* Composición

⸻

Unidad 3. Manejo de Estructuras

Estructuras de Control

* Condicionales
* Repetitivas

Estructuras de Datos

* Arreglos de objetos
* ArrayList
* Colecciones
* Serialización de objetos

⸻

Unidad 4. Herencia

* Implementación de herencia
* Superclases
* Subclases
* Niveles de acceso
* Invocación de constructores
* Jerarquías UML
* Navegabilidad
* Multiplicidad
* Roles en UML

⸻

6. Retroalimentación

Modelado UML

Comparar el UML del estudiante con la solución ideal generada.

Redactar:

* Máximo una línea.
* Señalar diferencias principales.
* Indicar mejora más importante.

⸻

Implementación Java

Comparar la implementación del estudiante con la solución ideal generada.

Redactar:

* Máximo una línea.
* Señalar diferencia principal.
* Indicar mejora más importante.

⸻

7. Evaluación

Generar un informe único con:

* Calificación cualitativa
* Puntaje obtenido
* Retroalimentación breve

Aplicando la siguiente rúbrica.

⸻

RÚBRICA DE EVALUACIÓN PARA LOS TALLERES DE RESOLUCIÓN DE PROBLEMAS CON HERENCIA, UML Y JAVA

⸻

CRITERIO: MODELADO

EXCELENTE (3.5 pts)

* Las clases representan correctamente la solución.
* La jerarquía de herencia es adecuada.
* Los atributos, métodos y relaciones son claros y coherentes.

SATISFACTORIO (2.8 pts)

* El modelado es correcto en su mayor parte.
* Presenta pequeñas omisiones o inconsistencias.

EN PROGRESO (2.1 pts)

* El modelado representa parcialmente la solución.
* Existen errores en clases, relaciones o herencia.

INICIADO (1.4 pts)

* El UML presenta múltiples inconsistencias.
* La estructura propuesta es poco clara.

AUSENTE (0.35 pts)

* No presenta UML o es totalmente incorrecto.

⸻

CRITERIO: IMPLEMENTACIÓN

EXCELENTE (3.5 pts)

* Implementa completamente el modelo diseñado.
* Aplica correctamente herencia, encapsulamiento y constructores.
* Presenta código claro y organizado.

SATISFACTORIO (2.8 pts)

* Implementa la mayoría de los requerimientos.
* Presenta errores menores de diseño o programación.

EN PROGRESO (2.1 pts)

* Implementa parcialmente la solución.
* Existen inconsistencias importantes respecto al UML.

INICIADO (1.4 pts)

* La implementación es incompleta o difícil de comprender.

AUSENTE (0.35 pts)

* No existe implementación o es totalmente incomprensible.

⸻

CRITERIO: RESULTADOS / FUNCIONALIDAD

EXCELENTE (1.5 pts)

* Todos los resultados son correctos.
* El programa funciona sin errores.

SATISFACTORIO (1.2 pts)

* Los resultados son mayormente correctos.
* Presenta errores menores.

EN PROGRESO (0.9 pts)

* Solo cumple parcialmente los requerimientos.

INICIADO (0.6 pts)

* Los resultados son incompletos o poco confiables.

AUSENTE (0.15 pts)

* No genera resultados válidos.

⸻

CRITERIO: VALIDACIÓN IA

EXCELENTE (1.5 pts)

* Presenta evidencias de revisión con IA y/o par académico.
* Integra mejoras relevantes derivadas de la retroalimentación.

SATISFACTORIO (1.2 pts)

* Utiliza la retroalimentación recibida.
* Realiza mejoras evidentes.

EN PROGRESO (0.9 pts)

* Revisa la retroalimentación, pero aplica pocas mejoras.

INICIADO (0.6 pts)

* Existe evidencia mínima de revisión o mejora.

AUSENTE (0.15 pts)

* No presenta evidencia de validación o mejora.

⸻

Puntaje Máximo

Criterio	Puntaje
Modelado	3.5
Implementación	3.5
Resultados / Funcionalidad	1.5
Validación IA	1.5
TOTAL	10.0