# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU2.pserrano.  Curso: 2019/20 

Proyecto: 

Descripción: 

Logotipo: 

Miembros
 * :bust_in_silhouette:   Pedro Serrano Pérez     :octocat:     


----- 

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

>>> Badi:

>>>> Permite publicar una habitación para buscar un inquilino y realizar una búsqueda para reservar y alquilar una habitación.
Posee un sistema de búsqueda que utiliza GoogleMaps para poder buscar una habitación en una ciudad concreta. Este sistema posee una herramienta para buscar alojamiento cerca de donde se encuentra el usuario actualmente usando la ubicación. No es necesario estar registrado para realizar una búsqueda.

>>> Couchsurfing:

>>>>Su principal objetivo es compartir una casa con viajeros y compartir experiencias en la ciudad del huésped, de forma que este actúa como guía para el viajero.
Cada usuario debe rellenar información sobre su estilo de vida y objetivos en su perfil. De esta forma es más fácil encontrar personas afines. 

>>> Compartetupiso:

>>>> Permite ofrecer y buscar alojamiento en función de la "experiencia" que el usuario quiere experimentar, es decir, en función de si desea compartir aficiones con alguien, trabajar en un campo relacionado (afinidad profesional), etc.
Los usuarios son verificados de forma manual y se comprueba que una persona puede realmente ofrecer un espacio. Los usuarios que ofrecen alojamiento pueden optar por cobrar o no un alquiler.
Cuando tratas de iniciar sesión, siempre aparece la misma pantalla con el mensaje “Gracias, ya tenemos tus datos, en breve te contactaremos.”

>>> Habitoom:

>>>> Es un sitio web cuyo objetivo es conectar personas que buscan un lugar para vivir con aquellas que ofrecen un sitio para alquilar.
Este sitio web trata de crear una comunidad para que todos aporten sus experiencias vividas de forma que sirvan como referencia a futuros inquilinos.
Permite realizar búsquedas de alquileres sin necesidad de registrarse, aplicando filtros en la búsqueda como metros cuadrados, número de inquilinos, edad de los inquilinos, etc.
Habitoom permite que el usuario no solo publique un espacio para alquilar o buscar uno, también permite crear alertas con ciertos filtros para que avisen al usuario cuando alguien ha publicado un alquiler que se adapte.
En el registro no se pide información como el sexo o la fecha de nacimiento del usuario, por lo que estos son asignados a un valor predefinido, por lo que el usuario ha de cambiarlos posteriormente. 
He escogido este sitio web debido a que posee un servicio premium que permite publicación ilimitada de espacios de alquiler, publicar todos los datos de contacto, etc.

![Método UX](img/Persona.png) 1.b Persona
-----

>>> Manuel

>>>> He escogido a Manuel debido a que acaba de finalizar sus estudios y quiere tomarse un tiempo libre antes de comenzar a trabajar. Hasta ahora sus padres pagaban los costes de sus estudios, alojamiento, etc, por ello se encuentra en una etapa crítica en la que debe volverse totalmente independiente en el aspecto económico y, por tanto, no tiene mucho tiempo hasta que tenga que adentrarse de lleno en el mundo laboral.

>>>Ficha Manuel:
[](P1/PersonaManuel.jpg)

>>> Gloria

>>>> Gloria, la otra persona que he elegido, se trata de una mujer divorciada de edad avanzada que lleva viviendo durante toda su vida en el mismo sitio y lleva trabajando durante muchos años como recepcionista en un hotel. Aunque tiene estabilidad tanto económicamente como en el ámbito personal su vida es muy monótona ya que lleva mucho tiempo viviendo en el mismo lugar y trabajando en el hotel.


![Método UX](img/JourneyMap.png) 1.c User Journey Map
----


>>> La experiencia de Manuel es bastante común. Una persona joven quiere ir de viaje, pero no tiene mucho dinero, por lo que busca compartir un piso/alquilar una habitación para no tener que gastar mucho en alojamiento. El problema es que debido a las prisas no utiliza la web adecuada para esta búsqueda, por lo que no queda nada satisfecho.

>>> La experiencia de Gloria es menos habitual, teniendo en cuenta que se trata de una persona con 50 años. Lleva toda su vida viviendo en el mismo pueblo, pero decide mudarse a la capital, donde trabaja, con una amiga. En este caso si utiliza una web adecuada, el problema viene cuando se encuentra con las carencias de la web, que para una persona no acostumbrada a navegar por internet o al uso de ordenadores pueden hacerle pasar un mal rato.


![Método UX](img/usabilityReview.png) 1.d Usability Review
----
>>> Usability Review: [Usability-review-DIU2-pserrano](P1/Usability-review-DIU2-pserrano.pdf)

>>> Valoración numérica: 67.

>>> El sitio web “Habitoom” tiene como finalidad poner en contacto a personas con el fin de alquilar una habitación. Trata de ser una especie de “red social” para alquiler de habitaciones.
Una de las principales desventajas es el periodo de estancia mínimo de 1 mes, que se debe a que está destinada a personas que se mudan por cuestiones de trabajo, estudios, etc. Esto hace que sea poco flexible e inviable para personas que buscan alojamiento para vacaciones o similares.

>>> En cuanto a la funcionalidad Habitoom cumple su objetivo. Proporciona las herramientas necesarias para poner un anuncio de una habitación o buscar una. A pesar de cumplir su objetivo posee carencias como la poca flexibilidad de su sistema de búsqueda, que solo permite buscar con el formato “Provincia, País”, lo cual es bastante incómodo para cualquier usuario. Otra de sus grandes desventajas es la poca información que se requiere para crearse una cuenta (e-mail, nombre y contraseña), el resto de campos de información o están predeterminados (sexo o fecha de nacimiento) o no es necesario completarlos (foto de perfil, descripción, etc), lo que hace que un usuario poco no modifique estos parámetros de su perfil.

>>> Por último, posee un servicio premium que permite publicar un número ilimitado de habitaciones y publicar el número de teléfono personal. Este aspecto es bastante negativo, ya que la mayoría de usuario no pagan dicho servicio, pero el número de teléfono es la mejor forma para comunicar a usuario normales (uso a aplicaciones de mensajería como “Whatsapp”) en casos como alquiler de piso o habitación. Esto provoca que el número de usuarios potenciales decrezca debido a las pobres formas que tiene el sitio web de poner en contacto a los usuarios.

>>> La conclusión es que, aunque ofrece las funcionalidades básicas para cumplir su objetivo, su filosofía de red social hace que sea una web inferior a muchas otras similares (en el ámbito de alquilar piso, compartir piso, etc).



## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----


>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior,


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  
  
  
>>> ¿Que planteas como "propuesta de valor" para un nuevo diseño de aplicación para economia colaborativa ?
>>> Problema e hipótesis
>>>  Que planteas como "propuesta de valor" para un nuevo diseño de aplicación para economia colaborativa te
>>> (150-200 caracteres)

![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----

>>> Definir "User Map" y "Task Flow" ... 


![Método UX](img/labelling.png) 2.c Labelling 
----


>>> Identificar términos para diálogo con usuario  

Término | Significado     
| ------------- | -------
  Login¿?  | acceder a plataforma


![Método UX](img/Wireframes.png) 2.d Wireframes
-----

>>> Plantear el  diseño del layout para Web/movil (organización y simulación ) 


## Paso 3. Make (Prototyping) 


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 

![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


## Paso 4. UX Check (Usability Testing) 


![Método UX](img/ABtesting.png) 4.a A/B Testing
----


>>> Comprobacion de asignaciones para A/B Testing. Asignaciones https://github.com/mgea/DIU19/blob/master/ABtesting.md

>>>> Práctica A: 


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Usuarios para evaluar prácticas 


| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.c Usability Report
----

>> Añadir report de usabilidad para práctica B 



## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión / Valoración de las prácticas


>>> (90-150 caracteres) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  







