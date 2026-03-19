# DIU26
Prácticas Diseño Interfaces de Usuario (Tema: .... ) 

* [Guiones de prácticas](GuionesPracticas/)
* [Guía para crea tu Case Study](Guia_CaseStudy.md)
* Sala de la Fama [DIU Hall of fame](https://github.com/mgea/DIU/tree/master/hall_of_fame) donde se pueden encontrar Case Study destacados de otros años.




Actualizado: 14/01/2026




## Paso 0 My UX-Case Study
![Método UX](img/caseStudy.png) 
-----

>>> Este documento es el esqueleto del Case Study que explica el proceso de desarrollo de las 5 prácticas de DIU. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. Elimine este tipo de texto / comentarios desde la práctica 1 conforme proceda a cada paso


>>> Hay que Publicar de forma incremental "my Case Study" en Github... Es el momento de dejar este documento para que sea evaluado y calificado como parte de la práctica
>>> Documente bien la cabecera y asegurese que ha resumido los pasos realizados para el diseño de su producto

Grupo: DIU1_JMDA.  Curso: 2025/26 

Nombre del Proyecto: 

>>> Decida el nombre corto de su propuesta en la práctica 2 

Descripción: 

>>> Describa la idea de su producto en la práctica 2 

Logotipo: 

>>> Si diseña un logotipo para su producto en la práctica 3 pongalo aqui, a un tamaño adecuado. Si diseña un slogan añadalo aquí

Miembros y nombre del equipo:
 * :bust_in_silhouette:  Jose María Martín     :octocat:     https://github.com/josemartin2912
 * :bust_in_silhouette:  David López Giménez     :octocat: https://github.com/Garromo14


----- 

<br>

# Proceso de Diseño 





<br>

## Paso 1. UX User & Desk Research & Analisis 



### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----


<img src="https://img.uxcel.com/cdn-cgi/image/format=auto/practices/user-research-1599142817996/a-1696512677044-2x.jpg" alt="UX Reaearch plan" style="height:250px" />

## 1 Descripción 



El establecimiento **Shifu Ramen** es un restaurante japonés especializado sobre todo en ramen y que combina la comida con la cultura del manga.


#### 1. Antecedentes y Objetivos (The "Why")

- **Contexto:** 

Con este estudio, se pretende realizar un análisis del comportamiento del usuario en este tipo de páginas web de restauración ( sobre todo japonesa ) con el fin de hacer un diseño y desarrollo de la aplicación del restaurante.


- **Objetivos de investigación:** 

Se pretende con este análisis que la aplicación cuente con una serie de características que optimicen la experiencia de usuario. Algunos de los más importantes son:

- Facilidad para el usuario de acceder al menú en un tiempo razonable.
- Accesibilidad para la gestión de reservas.
- Analizar qué comportamiento tienen los nuevos usuarios para atraer más usuarios.


- **Experiencia del equipo / justificación**

    - **Jose María Martín**: "Como desarrollador, he trabajado en otros proyectos de restauración y frecuento páginas de anime, por lo que este proyecto me es muy interesante".
    - **David López**: "Como Stakeholder, he estado en otros proyectos de restauración y quiero explotar el mercado del anime japonés."   
    - **María Alonso**: "Como empleada de otro sitio de ramen, observo que la gente quiere un espacio gastronómico de temática de anime para los fans de este género, pero que no sea demasiado cargante para posibles nuevos consumidores."




#### 2. Metodología (The "How")

Se pretenden seleccionar técnicas no muy complejas en este estudio, pues en una página de restauración se espera que el usuario haga un uso rápido como encontrar el menú o gestionar una reserva:

- **Entrevistas: Método cualitativo y actitudinal**.

- **A/B Testing + Eye tracking Método cuantitativo y de comportamiento**.

- **A/B Testing + Test de usabilidad: Método cualitativo y de comportamiento (test de usabilidad) y cuantitativo y de comportamiento ( A/B Testing )**.



<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*QkF2uE-NsI0piP90AQkF-A.png" alt="UX Reaearch Methods" style="height:450px" />

ref: https://www.nngroup.com/articles/which-ux-research-methods/

#### 3. Perfil de los Participantes (The "Who")

Como se ha comentado previamente, distinguimos dos grupos de posibles usuarios, afines a la cultura del anime y personas ajenas a esta cultura. Se seleccionan **25 participantes** para entrevistar, distribuidos en:

- **20 participantes interesados en el anime**, de edad joven ( 16-35 años ). 
- **5 participantes no interesados en esta cultura**, de edad variable.

En cuánto a los métodos diferentes a las entrevistas, seleccionamos un subrgupo de estos 25 participantes, formado por **8 personas del primer subgrupo** sumado a **2 personas del segundo grupo**, concretamente 1 adulto y 1 persona de edad avanzada.


#### 4. Guion y Tareas (The "What")

En los experimentos donde el usuario tenga contacto con la aplicación, algunos son:

- Navegar libremente por la interfaz y preguntar por opinión, sus objetivos, en qué ha tenido éxito, en qué ha fracasado... etc.
- Buscar el menú y observar 5 productos de diferente categoría ( p.e. bebidas, ramen, postres...).
- Encontrar el horario y localización del establecimiento.
- Realizar una reserva y comprobar que se ha realizado con éxito.
- Encontrar el contacto del restaurante y sus redes sociales.

#### 5. Cronograma y Entregables

- Análisis de competencia 
- 2 Documentos "Personas" para conocer varios perfiles potenciales de usuarios.
- 2 "User Journey Map" para entender la interacción del usuario con la aplicación.
- Usability Report con mejoras de usabilidad.

[Research Plan Completo (más detallado)](P1/resources/UserResearchPlan.md)


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----
![Analisis](P1/img/CompetitorAnalysis.png) 

Shifu Ramen Granada es un establecimiento con una pagina web muy sencilla. Está diseñada para usarse como una carta on-line, ya que al abrir es lo primero que aparece; sin embargo, también dispone de funcionalidad para hacer otras cosas como una reserva o mirar las novedades en su blog. 

Buga Ramen por otra parte tiene una pagina web más compleja y vistosa. Destaca por ofrecer más información sobre su historia y sus locales, con una gran galería de fotos. Por este enfoque más centrado en vender la experiencia, han dado a cambio otras funcionalidades como la posibilidad de reservar por teléfono.

Hemos decidido decantarnos por Shifu Ramen puesto que tiene un flujo de usuario más completo, permitiendo realizar reservas directamente desde la web. Además, tiene un enfoque más interactivo que la alternativa, con un blog en la propia web y con su presencia en las redes sociales que creemos que puede ser más interesante a la hora de realizar un análisis.



### 1.c Personas
![Método UX](img/Persona.png) 
-----
![Persona #1](P1/img/Persona1.png)

Andrés es un informático joven con una gran afición por el anime. Por esto, Andrés es un ejemplo claro del publico objetivo del restaurante.

![Persona #2](P1/img/Persona2.png) 

Guillermo por otra parte es una persona que no tiene ningún interes en el restaurante, sin embargo le gusta probar comidas nuevas y está dispuesto a probar en Shifu Ramen. 


### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----
![Journey Map #1](P1/img/User_Journey_Map_1.jpg) 

Andrés tiene una experiencia bastante tipica en la que mira datos como los alérgenos y cuando tieme toda la información que necesita hace una reserva.

![Journey Map #2](P1/img/User_Journey_Map_2.jpg) 

La experiencia de Guillermo ejemplifica como el uso de la web es muy parecido aunque no forme parte de su público objetivo y nos proporciona información sobre cómo se desenvuelve la página web con otros tipos de usuario.


[Justificación Persona y Journey Map 1](P1/resources/JustificacionPersonaYJourneyMap1.pdf)

[Justificación Persona y Journey Map 2](P1/resources/JustificacionPersonaYJourneyMap2.pdf)

### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----
[Usability Review](P1/resources/Usability-review.xlsx)
[Usability Review pdf](P1/resources/Usability-review.pdf)

Valoración final: 82/100
Al hacer el análisis de usabilidad comprobamos que se desenvuelve bastante bien en normas generales, aunque hay algunos puntos en los que flaquea. Por ejemplo, el hecho de que puedas acceder a una página de administrador protegida con contraseña desde la página principal es un error grande y debería arreglarse con urgencia. Además, al ser una página web sencilla y con poca interactividad, hay secciones que no se pueden calificar de forma completa.

### 1.f Briefing de la práctica
Este proyecto tiene como objetivo el análisis de usabilidad del sitio web https://www.ramenshifu.com/ramen-shifu-granada/. Para ello, se han llevado a cabo las siguientes pruebas:

- Research Plan.
- Competitor Analysis.
- Documentos “Personas” y “User Journey Map”.
- Usability Review.
    
Estas pruebas tienen como objetivo describir un conjunto de prácticas y metodologías que aplicar a los usuarios del sitio web, describiendo a estos usuarios y las acciones potenciales a realizar y analizando la competencia  con el objetivo de evaluar y mejorar la usabilidad de nuestra aplicación.
Las pruebas han dado resultado a las siguientes conclusiones:

- El sitio cumple con lo esperado en una página web de restauración, es decir, un uso rápido y sencillo del usuario.
- La temática de anime está presente y no sobrecarga la experiencia de usuario.
- El menú está presente en la página principal y bien distribuido por categorías.
- Elementos como la dirección o el contacto son fáciles de encontrar en la cabecera.
- Los alérgenos no se encuentran a simple vista.
- El apartado reservas es claro y bien estructurado.
- Hay ciertas secuencias de navegación que conducen a páginas que parecen obsoletas.

[Briefing Completo](P1/resources/BriefinfUsabilityReview.pdf)
### 1.g Valoración del equipo

En general, damos por satisfactoria la realización de la práctica. La comunicación del equipo ha sido buena y la carga de trabajo se ha repartido de forma equitativa. Además, se ha utilizado los recursos de forma homogénea como por ejemplo la misma plantilla de "Personas".

<br>

## Paso 2. UX Design  

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior. De qué carece la competencia?? Tu diagrama puede ser una figura subida a la carpeta P2/


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  
    
>>> Explica el Problema y plantea una hipótesis. Es decir, explica aquí qué 
>>> se plantea como "propuesta de valor" para un nuevo diseño de aplicación propio


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

>>> Propuesta de valor, pero ahora en vez de un texto es un ScopeCanvas que has subido a P2/ y enlazado desde aqui. Tambien vale una imagen miniatura del recurso.
>>> No olvides que tu propuesta ya tiene un nombre corto y puedes actualizar la cabecera de este archivo



### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

>>> Definir "User Map" y "Task Flow" ... enlazar desde P2/ y describir brevemente


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

>>> Identificar términos para diálogo con usuario (evita el spanglish) y la arquitectura de la información. Es muy apropiado un diagrama tipo sitemap y una tabla que se ampliaría para llevar asociado la columna iconos (tanto para la web como para una app). 

Término | Significado     
| ------------- | -------
  Login  | acceder a plataforma


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

>>> Plantear el diseño del layout para Web/movil (organización y simulación). Describa la herramienta usada 

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




