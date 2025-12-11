# MOD_6_GRUPAL_1


M6_AE1_ABPRO-Ejercicio grupal[Actividad Evaluada]

Ejercicio grupal
Contexto de la actividad

Forman parte de un equipo de desarrollo que está iniciando un nuevo proyecto de software en Java. El equipo de arquitectura les ha solicitado que construyan la estructura base del proyecto, asegurándose de que el proyecto tenga buena configuración, dependencias bien gestionadas, pruebas iniciales, empaquetamiento y ejecución funcional.
Además, deben documentar el proceso y justificar sus decisiones técnicas, como si fueran a presentarlo al resto del equipo.


Instrucciones

Paso 1: Creación del proyecto base con Maven en STS

Usando STS, creen un nuevo proyecto Java con Maven.

Elijan entre crear un proyecto con SpringMVC o con SpringBoot, y justifiquen su elección.

Configuren el archivo pom.xml incluyendo:

Datos básicos (groupId, artifactId, version)

Al menos 3 dependencias relevantes para su elección (por ejemplo: Spring Web, Thymeleaf, JUnit, etc.)

Paso 2: Simulación del flujo de desarrollo con Maven

Ejecuten desde STS o terminal los siguientes comandos de Maven y documenten su efecto:

mvn clean

mvn compile

mvn test

mvn package

mvn install

Expliquen qué generó cada comando y en qué parte del ciclo de vida del proyecto intervinieron.

Paso 3: Integración de un formulario con validación básica

Creen un formulario HTML o JSP que capture un par de datos (nombre y edad, por ejemplo).

Envíen esta información a través de un controlador (puede ser un Servlet simple si aún no están usando SpringController).

Validar que los datos no estén vacíos y que la edad sea un número válido antes de aceptarlos.

Paso 4: Manejo de dependencias, repositorios y estructura

Expliquen cómo se descargaron las dependencias.

Localicen el repositorio local de Maven y detallen qué tipo de archivos contiene.

Muestren y expliquen la estructura del proyecto generada por Maven (src/main/java, src/main/resources, etc.).

Paso 5: Documentación y presentación

Documenten el proceso completo de configuración, decisiones tomadas, errores encontrados y soluciones.

Preparen una presentación corta para explicar:

Qué configuraron en el pom.xml

Cómo resolvieron las validaciones

Qué aprendieron sobre el ciclo de vida de Maven y los comandos utilizados


Producto final esperado

Cada equipo debe entregar:

El proyecto funcionando en un repositorio compartido o comprimido (.zip)

Un documento explicativo (puede ser PDF o presentación) que resuma el proceso

Capturas del formulario en funcionamiento y del resultado de los comandos Maven

Ejecución: Grupal.
