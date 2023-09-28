# Universidad Peruana de Ciencias Aplicadas.
### Ingeniería de Software.
### Aplicaciones Web
### SW53
#### Naldo Reupo Musayon Gastulolo
---

# Proyecto del Curso.

## TB1 REPORT

### StartUp Name
Open Developers
### Team Members

|             Members             |    User    |
|:-------------------------------:|:----------:|
|   Curi Montero, Jonatan Omar    | u201912404 |
|   Puican Salas, Kurt Matthews   | U202016643 |
|   Luyo Ramirez, Rafael Arturo   | u202115348 |
| Ramos Calderon, Giovanni Andres | u202122512 |
| Ramirez Alfaro, Miguel Angel    | u20201b895 |

#### Ciclo 2023 - 02

<br><br>

## Registros de versiones del Informe

|   Version     |   Fecha   |   Autor   |   Descripción de la modificación|
|:-------------:|:---------:|:---------|:------------------------|
|1              | 7/09/23   |Ramirez Miguel|- Implementó  capitulo 3|
|1              | 7/09/23   |Curi Montero|- Implementó Mockups, landing page, prototipo y Sprint 1 |
|1              | 31/08/23  |Luyo Ramirez |- Implementó 4.1, 4.2, 4.3, 4.8  |
|1              | 7/09/23   |Puican Kurt|- Implementó  capitulo 1 y 2|
|1              | 8/09/23   |Ramor Giovanni|- Implementó  5.1, 4.6 y 4.7|

<br><br>

# Índice

## 1. Capítulo I: Introducción

- [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3 Segmentos objetivo](#13-segmentos-objetivo)

## 2. Capítulo II: Requirements Elicitation & Analysis

- [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)

## 3. Capítulo III: Requirements Specification

- [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2 User Stories](#32-user-stories)
- [3.3 Impact Mapping](#33-impact-mapping)
- [3.4 Product Backlog](#34-product-backlog)

## 4. Capítulo IV: Product Design

- [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
- [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
- [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.7.2 Class Dictionary](#472-class-dictionary)
- [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagram](#481-database-diagram)

## 5. Capítulo V: Product Implementation, Validation & Deployment

- [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X Sprint n](#52x-sprint-n)
        - [5.2.X.1 Sprint Planning n](#52x1-sprint-planning-n)
        - [5.2.X.2 Sprint Backlog n](#52x2-sprint-backlog-n)
        - [5.2.X.3 Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
        - [5.2.X.4 Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
        - [5.2.X.5 Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
        - [5.2.X.6 Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
        - [5.2.X.7 Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
        - [5.2.X.8 Team Collaboration Insights during Sprint](52x8-team-collaboration-insights-during-sprint)

<br>

# Student Outcome
| Criterio específico | Acciones Realizadas | Conclusiones |
|:--------------------|:-------------------:|:------------:|
|Comunica oralmente con efectividad a diferentes rangos de audiencia|Tareas| Conclusion de Student Outcome|
|Comunica por escrito con efectividad a diferentes rangos de audiencia|Tareas|Conclusion de Student Outcome|
<br><br>

# Capitulo 1: Introducción

## 1.1 Startup Profile

A continuación, procederemos a informar sobre a lo que se dedica nuestra producto “StudyMentor”, así como la presentación del equipo de desarrollo del producto, software presentado anteriormente, “Evosoft”

### 1.1.1 Descripción de la Startup

En la actualidad hay mucha gente que sufre en sus carreras ya sea por que no entienden los temas que se están abordando en sus respectivas carreras como también por que quieran tener un repaso antes de un examen, como también cómo buscar alguna ayuda al momento de realizar un trabajo y no saben por dónde empezar. Uno de los problemas de por que varios alumnos busquen un asesoramiento para varios temas de su carrera se debe a la pandemia, ya que en esta varias de las clases se dieron de manera virtual y gracias a esto había varios alumnos que no prestan atención a las clases y por consecuencia no entendían lo que estaban enseñando haciendo que los alumnos se estresen por no entender los temas.
Por estas razones y otras más, hemos decidido en crear este producto llamado “StudyMentor”. Somos una empresa emergente con posibilidades bastante óptimas con respecto al crecimiento de esta. En una primera instancia, no contamos con mucha clientela, pero estamos enfocados y decididos a crecer como empresa usando el potencial de las tecnologías móviles.
Nuestra misión como empresa actualmente es encontrar una manera fácil para poder ayudar a los estudiantes que tienen problemas con sus estudios para que puedan nivelarse y poder estar a la par de las expectativas de los estudios. Crearemos un software que pueda apoyar a los alumnos a poder encontrar profesores o asesores en los ámbitos que están buscando aprender y mejorar, de igual manera nuestra visión es convertirnos en una gran opción cuando se trata de poder ayudar a los alumnos.


### 1.1.2 Perfiles de integrantes del equipo

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Foto</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Miembro</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Habilidades</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Codigo</th>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="" alt="" width="60" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149207235973632050/foto.jpg" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Kurt Puican Salas</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Soy Kurt Puican Soy un estudiante de la carrera de ingeniería de software y a lo largo de toda la carrera he ido aprendiendo diversos temas como los lenguajes de programación, los patrones de diseño entre varias otras cosas y es una carrera que me gusta bastante ya que desde pequeño siempre me ha gustado lo que tiene que ver con la tecnología.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">U202016643</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://cdn.discordapp.com/attachments/1149190528756363338/1149190749762637884/FotoRafaelLuyo.jpg" alt="FotoRafaelLuyo" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Luyo Ramirez, Rafael Arturo</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Rafael Luyo, tengo 21 años. Me considero una persona agradable, puntual y respetuosa. Elegí mi profesión actual porque disfruto haciendo varios ejercicios o problemas relacionados con el uso de la programación, además de interesarme mucho la malla curricular. Me motiva aprender cosas nuevas y también la futura estabilidad económica.  </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u201919295</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/783068752958717972/1149867780959637645/image.png" alt="FotoJonatanCuri" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Curi Montero, Jonatan Omar</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Jonatan Curi, soy un estudiante de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). Tengo 21 años, soy una persona responsable, amable y con la iniciativa de trabajar. Poseo conocimientos en los lenguajes TypeScript y Javascript. También, en frameworks como NestJS y Angular. Considero que la comunicación es una característica fundamental en el equipo de trabajo.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">U201912404</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/736250121276096522/1157086857516040222/foto_TP.png?ex=6517549c&is=6516031c&hm=9ce15fd917e4c5a0f33a0131de254967a3bdfb4eb391ec436d52e9a1c0407c61&=&width=558&height=676" alt="FotoGiovanniRamos" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Ramos Calderon, Giovanni Andres</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Giovanni Ramos, tengo 19 años y soy estudiante de la carrera Ingeniería de Software. Me interesan los temas relacionados a la arquitectura de una aplicación web. Así mismo me gusta aportar con la programación de un proyecto. Considero que puedo aportar con ideas y cooperar con los integrantes del equipo para los avances del trabajo.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202122512</td>
  </tr>
</table>

## 1.2 Solution Profile

En este punto del informe, daremos una explicación de nuestro producto de software, así como también la forma de generar ingresos.
 
Product Name
 
Hemos optado por el nombre de “StudyMentor” hemos usado el nombre en inglés para generar más atractivo en los usuarios “StudyMentor” se conforma por dos palabras en inglés que hacen referencia a lo que hace el software ‘Study’ quiere decir estudio haciendo referencia a los estudiantes que necesitan apoyo en los estudios que requieran y ‘Mentor’ que quiere decir Mentor que hace referencia a los asesores que ayudarán a los alumnos en los estudios.
 
Product Descrition
En esta web se les da a los usuarios la facilidad de poder encontrar mentores o profesores de diferentes áreas en la pagina podrán buscar tutores según el área de estudio que los estudiantes estén buscando podrán ver la valoración del tutor el costo que tiene y si es que se convence poder agendar una sesión de estudio. Los tutores por otra parte tienen la facilidad de poder subir sus datos para que los alumnos puedan encontrarlos y puedan elegirlos para esto tienen la facilidad de subir su CV y la experiencia que han tenido a lo largo de su carrera, como también la facilidad de poder incluir los datos para poder contactarlo.
 
Monetization
En nuestro servicio nosotros actuamos como un intermediario entre los alumnos y los tutores y al momento de que se genere una clase nosotros no llevamos una parte del pago de los asesoramientos.
 
## 1.2.1 Antecedentes y problemática del producto
Descripción de la problemática
 
Este software se enfoca en el sector educativo, ya que en los tiempos actuales donde muchas personas necesitan un pequeño asesoramiento para apoyar a los estudiantes para que se nivelen en los estudios “StudyMentor” sirve de intermediario para poder encontrar gente con experiencia en los diversos ámbitos que se requieran cubrir por los alumnos.
 
**Objetivos**

Este software tiene el principal objetivo de apoyar al estudio de los estudiantes por medio de un intermediario con tutores que sepan de los temas que los alumnos quieren aprender, también buscamos ser una gran alternativa al momento en el que un usuario quiera buscar alguien que le enseñe temas que este no comprenda.
 
**Restricciones**

Una principal restricción que delimita el alcance del proyecto es que el equipo desarrollador es nuevo en estas tendencias o técnicas a aplicar para lanzar nuestra aplicación. Por ello, es que puede ser una restricción de alcanzar el mejor escenario. Sin embargo, el equipo pondrá de su parte para lograr alcanzar el nivel deseable de cada entregable.
 
**Antecedentes**

Como ya se ha mencionado a lo largo del informe nuestro producto tienen la capacidad de conectar tutores con estudiantes, sin embargo, hay algunos servicios que tienen características similares con nuestro producto es por eso hemos investigado a posibles competidores para poder mejorar nuestro producto.
TutorFinder:
Descripción: TutorFinder es una plataforma en línea que conecta a estudiantes con profesores en una amplia variedad de materias y niveles. Los usuarios pueden filtrar por ubicación, materia, nivel educativo y experiencia del profesor para encontrar el tutor perfecto.
 EduTutores:
Descripción: EduTutores es una comunidad en línea donde estudiantes pueden encontrar profesores para recibir ayuda en asignaturas específicas. Los profesores pueden establecer sus tarifas y horarios, y los estudiantes pueden reservar sesiones según su conveniencia.

**Herramienta de 5W y 2H**

o **What** - ¿Cuál es el problema?
▪ El problema identificado es la cantidad de estudiantes que necesitan asesoramiento en diversos temas de aprendizaje tratados en sus respectivas universidades y/o institutos ya que no se pudo llegar a comprender los temas tratados en clase
 
o **When** - ¿Cuándo sucede el problema?
▪ Cuando es un estudiante no llega a comprender alguna clase y se encuentre perdido ya sea por que el tema resulto ser demasiado difícil como también por que no se llego a prestar la suficiente atención, así como también cuando algún estudiante requiera un reforzamiento en los temas tratados en clase
 
o **Where** - ¿Dónde surge el problema?
▪ El problema surge en distintas áreas educativas ya sean universidades, institutos o instituciones privadas
 
o **Who** - ¿Quiénes son afectados por el problema?
▪ Los principales afectados son los jóvenes estudiantes que están cursando su carrera
 
o **Why** - ¿Cuál es la causa del problema?
▪ La causa del problema es principalmente se puede deber de diversos factores como que el tema resulto ser demasiado difícil no llegaron a explicar de una buena manera el tema abordado como también estuvieron distraídos en clase.
 
o **How** - ¿Cómo se llevan a cabo los hechos?
▪ Cuando un estudiante requiera asesoramiento en los temas que este prefiere se dirige a la página web www.studymentor.com para poder conseguir algún profesional que le pueda dar el asesoramiento necesario para poder nivelarse y estar a la par que sus otros compañeros como también de lo esperado por la institución educativa
 

o **How much** - ¿Cuál es la magnitud del problema?
▪ La pandemia de COVID-19 ha llevado a un aumento en la educación a distancia y en línea, lo que puede hacer que algunos estudiantes se sientan más aislados y necesitan más apoyo en línea. Algunos estudiantes pueden tener dificultades particulares en ciertas materias o temas, lo que los lleva a buscar ayuda adicional tanto con sus trabajos como estudios ya que no es lo mismo aprender en presencial como en línea. Otro de los problemas es que varios alumnos se distraen en clases por lo que tampoco pueden entender las clases.

## 1.2.2 Lean Ux Process
### 1.2.2.1 Lean UX Problem Statement 

Problem Statement
En el panorama educativo actual, los estudiantes a menudo se enfrentan a desafíos al buscar profesores adecuados para recibir tutoría personalizada. A medida que la demanda de apoyo educativo fuera del aula sigue creciendo, surge la necesidad de una solución eficiente y confiable que conecte a los estudiantes con profesores calificados y compatibles. La falta de una plataforma integral y centralizada dificulta que los estudiantes encuentren profesores que se ajusten a sus necesidades y preferencias de aprendizaje.

Las búsquedas tradicionales de profesores a menudo implican una inversión significativa de tiempo y recursos, con resultados inciertos. Los estudiantes pueden encontrarse con problemas como la falta de información suficiente sobre los antecedentes y la experiencia de los profesores, la dificultad para coordinar horarios y ubicaciones, y la incertidumbre sobre la calidad de la enseñanza ofrecida. Además, el proceso de búsqueda y selección puede ser abrumador, especialmente para aquellos que buscan profesores en áreas específicas o con habilidades particulares.

La falta de una plataforma eficiente y confiable para conectar a estudiantes con profesores también puede afectar negativamente el rendimiento académico de los estudiantes. La ausencia de un acceso sencillo a tutores y mentores de calidad puede resultar en dificultades persistentes en el aprendizaje y una menor confianza en las propias habilidades académicas.
Por lo tanto ¿Como podemos hacer para que los estudiantes reciban una asesoria de los profesores de una manera facil tanto para los profesores como los alumnos para poder generar una clase?

### 1.2.2.2 Lean UX Assumptions

**Business Outcomes**

·         Generar una plataforma intuitiva, eficaz y óptima que genere ingresos a partir de la contratación de profesionales de diversos sectores educativos dispuestos a brindar sus servicios al estudiante

·         Establecer nuestra posición en el mercado, a través de resultados efectivos de los estudiantes que generará confianza en el público objetivo, calidad del servicio de los profesionales educativos y un sistema web sólido como práctico.

·         Causar interés en las empresas audiovisuales afiliadas de nuestra competencia, debido a nuestro alcance en los usuarios y su favoritismo, para ampliar nuestro alcance en publicidad, aumento de ingresos por el crecimiento de ventas, entre otros factores para el beneficio de la plataforma.

·         Producir una rentabilidad económica por los servicios de los profesionales educativos, con precios económicos y variables dependiendo de la necesidad del usuario, en el servicio de consultas vía sitio web o por un profesional, y la publicidad de nuestra plataforma con el fin de generar mayores ingresos que costos.

·         Sentar una tasa de retención por determinado periodo, para verificar si nuestros usuarios siguen utilizando nuestro servicio, con campañas de marketing, servicio que cumple sus necesidades con funciones de la plataforma, y si no se cumple, identificar cuáles serían las razones del abandono del servicio.

**Users**

·         Publico joven estudiantes de universidad o de instituto

·         Profesionales que sepan de los temas que los estudiantes quieran aprender
 
**User Outcomes**
 
**Faeatures**
1. **Creo que mis usuarios necesitan,** empezando por los estudiantes, recibir rápidamente variedad de profesores que puedan darle un asesoramiento para generar una clase. Por parte de los profesores tener la posibilidad de poner sus horarios y precios y las materias que dominan para poder ser escogidos por los alumnos.
2. **Estas necesidades se pueden resolver con** una plataforma que permita contactar a un profesional para que realice una asesoría  en nuestra plataforma de manera eficaz. Por otro lado, que le permita al estudiante coordinar la hora y los temas a desarrollar en la asesoria 
3. **Mis clientes iniciales son (o serán)** los estudiantes que necesiten o quieran una asesoria por un profesional  y, los profesionales que den estas asesorias. 
4. **El valor #1 que un cliente quiere de mi servicio es,** empezando por los estudiantes, recibir asesorías de manera cómoda, rápida y personalizada. Por otro lado, los profesionales desean conseguir asesorias para poder conseguir ingresos extra.
5. **El cliente también puede obtener beneficios adicionales,** Empezando por los estudiantes, podrían querer tener la oportunidad de calificar el servicio de los asesores por medio de un sistema de estrellas y comentarios, por otro lado los profesores quisieran tener la oportunidad de si es que son calificados de buena manera tener la posibilidad de ser encontrados más fácilmente en el buscador 
6. **Voy a adquirir la mayoría** de mis clientes a través de marketing en los medios de comunicación más frecuentados como Facebook, Instagram o entre otros; con la publicación de casos de éxito de los estudiantes que utilizan nuestra plataforma. Asimismo, demostrando las funcionalidades de las asesorías
7. **Haremos dinero a través** de la una comisión de las clases que se den en nuestra plataforma, ya que nosotros actuamos como un intermediario nosotros nos llevaremos un pequeño porcentaje de cada clase que se de en nuestra plataforma

---
1. **¿Quién es el usuario?**

Nuestros usuarios son aquellas personas que quieras mejorar o aprender diversos temas que se enseñan en los diversos sistemas educativos asi como tambien personas que proporcionen estas asesorías

2. **¿Dónde encaja nuestro producto en su trabajo o vida?**

En este caso encaja en cualquier momento de la vida de nuestros usuarios ya que pueden requerir los servicios en cualquier momento que estos lo vean necesario.

3. **¿Cómo y cuándo es usado nuestro producto?**

Para los estudiantes a través de nuestra página web a través de la cual van a contactar y a coordinar todo lo relacionado con las asesorías, y estas pueden ser en cualquier momento ya que al encontrar un profesor que sea del agrado del estudiante éste le mandará un mensaje al asesor con lo cual este solo tendrá que esperar a que el asesor le proporcione una respuesta y puedan coordinar de una mejor manera las asesorías.

 4. **¿Qué problema tendría nuestro producto y cómo se pueden resolver?**

Nuestro producto está desarrollado en plataformas digitales, por lo que, al ser personas de tercera edad la mayoría de profesores, se pueden generar complicaciones al momento de entender el correcto funcionamiento de ella. 

5. **¿Qué características son importantes?**

 Debe ser intuitiva, las opciones que tendrá la plataforma deben ser específicas y prácticas para que el usuario no tenga complicaciones en su uso. A su vez, el tiempo de respuesta en cuanto a la atención al cliente. 

 6. **¿Cómo debe verse nuestro servicio y cómo debe comportarse?**

www.Studymentor.com  Nuestro producto debe verse práctico, moderno y con contrastes de colores suaves; todo esto con la finalidad de hacer más satisfactoria la experiencia de usuario. Asimismo, debe comportarse como una interfaz fluida y con un manejo eficaz de la información.

### 1.2.2.3 Lean UX HYpothesis Statements

1st Hypothesis Statement

**Creemos que** el uso de nuestra plataforma facilitará la comunicación entre el usuario y el asesor y asi desarrollar las clases 

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que el 70% de los usuarios están satisfechos con la prontitud que se contacta a un asesor a través de sus reseñas positivas en nuestra plataforma.
 
2nd Hypothesis Statement

**Creemos que** publicar comentarios sobre experiencias con las asesorias para que otros usuarios puedan animarse a realizar una asesoria

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que un 60% entrar a la plataforma y conseguir una asesoria 
 
3rd Hypothesis Statement

 **Creemos que** publicar los asesores mejor valorados para demostrar que nuestro servicio contrata a profesionales para apoyar a los alumnos.

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que un 50% de nuestros usuarios utilizan las recomendacione los asesores para saber a quienes llamar

### 1.2.2.4 Lean UX Canvas

<table>
  <tr>
  <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="2">Título: StudyMentor</th>
    <th style="border:1px solid #dddddd; padding: 8px; text-align:center;">Fecha: 27/08/2023</th>
  </tr>
  <tr>
   <tr>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Business problem

Hemos identificado una problemática en este proceso los estudiantes, necesitan un apoyo extra para poder entender los cursos como también realizar los trabajos que se piden a lo largo de varios cursos en toda la carrera. Y a su vez asesores quieren poder ganar algo de dinero extra prestando sus servicios como asesores de estos alumnos que requieran una asesoría con un curso o trabajo
</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">Solutions

​​Plataforma que permita conectar a los asesores con los estudiantes para poder coordinar una asesoría.

Poder encontrar profesores de acuerdo a las necesidades de los estudiantes 
</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Business Outcomes

Generar una plataforma intuitiva que genere ingresos a partir de comisiones de acuerdo a cada asesoría llevada a cabo en la plataforma.
Establecer nuestra posición en el mercado a través de resultados efectivos de los estudiantes generando confianza por nuestro servicio
 Causar interés en las empresas audiovisuales afiliadas de nuestra competencia, demostrando que los usuarios nos prefieren a nosotros, para así ampliar nuestro alcance en publicidad, aumento de ingresos por el crecimiento de ventas, entre varios otros factores en beneficio de la plataforma
</td>
</tr>

  </tr>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Users 

Estudiantes que necesiten un asesoramiento en trabajos y cursos de la carrera

Profesionales en los cursos para darles asesoría
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">User Outcomes & Benefits

Poder conseguir un asesor del curso que quieras de una manera rápida y sencilla.
Identificar el proceso de mejora en los usuarios que usen la plataforma
Producir una mejora económica en los asesores que usen nuestra plataforma 
</td>
  
  </tr>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Hypotheses

Creemos que el uso de nuestra plataforma facilita la búsqueda de asesores para los estudiantes

sabremos que hemos tenido éxito cuando veamos que el 70% de los estudiantes está conforme con los resultados de las asesorías 

Creemos que la plataforma ayudará a los estudiantes con sus estudios 

Sabremos que hemos tenido éxito cuando veamos un 60% de de nuestros usuarios escribiendo comentarios en nuestra plataforma contando su experiencia que fue favorable
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">What is the most important thing we need to learn first?

Conocer las estadísticas de los estudiantes que requieran de una asesoría 

Conocer las estadísticas de los asesores que quieran generar ingresos dando asesorías 
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">What is the least amount of work we need to do to learn the next most important thing?

Entrevistas/ reuniones con nuestros clientes.

ver la conformidad de los usuarios al realizar las asesorías

inspeccionar la actividad de la plataforma para identificar errores en ella para poder solucionarlos
</td>
  </tr>
    
</table>

## 1.3 Segmento Objetivo
Nuestra plataforma StudyMentor se dirige a un amplio segmento de estudiantes que buscan asesoramiento educativo en diversas áreas para mejorar su rendimiento académico y alcanzar sus objetivos educativos. Este segmento incluye:

**Estudiantes en Diferentes Niveles Educativos:**
Nuestro público objetivo abarca estudiantes de todos los niveles educativos, desde secundaria hasta universidad. Esto incluye estudiantes universitarios que buscan destacar en sus estudios, estudiantes de secundaria que se preparan para exámenes cruciales, y aquellos que buscan especialización en campos particulares.

**Profesionales Jóvenes en Búsqueda de Desarrollo Continuo:**

También nos dirigimos a profesionales jóvenes que desean mejorar sus habilidades y conocimientos para avanzar en sus carreras. Esta categoría incluye a aquellos que buscan adquirir nuevas habilidades relevantes para su campo laboral.

**Perfil de Profesores en StudyMentor:**

Nuestra comunidad de profesores en StudyMentor está formada por profesionales altamente calificados y comprometidos con el éxito educativo de los estudiantes. El perfil de nuestros profesores se caracteriza por:

Cada profesor en nuestra plataforma tiene una amplia experiencia en su campo académico o profesional. Muchos de ellos poseen títulos avanzados y han demostrado un historial sólido de éxito en la enseñanza y/o en su industria.

Flexibilidad y Personalización:
Nuestros profesores comprenden las diversas necesidades de los estudiantes y pueden adaptar su enfoque de enseñanza según el estilo de aprendizaje y los objetivos individuales de cada estudiante.

# 2. Requirements Elicitation & Analisis
## 2.1 Competidores 
## 2.1.1 Analisis Competitivo 
<table style="border-collapse: collapse; width: 100%;"> 
<tr>
  <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="4">Competitive Analysis Landscape</th>
</tr>

  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">¿por que hacer este análisis?</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="3">¿Cómo identificar a nuestros principales competidores?
  </tr>
  <tr>
  <td colspan="3" style="border:1px solid #dddddd; padding: 8px; text-align:center;">Con este análisis, podemos identificar el FODA, es decir, las fortalezas, 
oportunidades, debilidades y amenazas de nuestros competidores. 
Asimismo, se evalúa su participación en el mercado y qué estrategias se 
pueden desarrollar para que nuestra aplicación surja en el mercado laboral. 
Pero ¿Cómo identificamos a nuestros principales competidores?, Debemos 
estudiar el mercado e identificar las aplicaciones más usadas por los estudiantes que quieran una asesoria . Así se concluyó 
que los principales competidores son:
</td>

  </tr>
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Imagenes de Competidores</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393830894903296/image.png" alt="" width="" height="" />
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393803376066651/image.png" alt="" width="" height="" /></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393776276668496/image.png" alt="" width="" height="" /></td>
  </tr>
    <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Overview</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Tutor.com es una plataforma de tutoría en línea ampliamente utilizada que ofrece a los estudiantes la oportunidad de obtener ayuda con una variedad de materias académicas. Los estudiantes pueden conectarse con tutores en tiempo real a través de chat en vivo y pizarra interactiva, lo que les permite hacer preguntas, resolver problemas y recibir explicaciones en tiempo real. El servicio está disponible las 24 horas del día, los 7 días de la semana, por lo que los estudiantes pueden acceder a la ayuda que necesitan en cualquier momento. Tutor.com también ofrece recursos de aprendizaje, como ejercicios de práctica y lecciones pregrabadas.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Chegg Tutors es una plataforma que conecta a estudiantes con tutores en línea en una amplia variedad de materias, desde matemáticas y ciencias hasta escritura y humanidades. Los estudiantes pueden buscar y seleccionar a un tutor basándose en sus necesidades específicas y programar sesiones de tutoría en línea a través de videoconferencia. Los tutores en Chegg Tutors son expertos en sus respectivos campos y pueden proporcionar explicaciones claras y ayudar a los estudiantes a resolver problemas académicos.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Wyzant es un servicio de tutoría en línea y en persona que permite a los estudiantes encontrar tutores locales o en línea para recibir apoyo en sus estudios. Los estudiantes pueden buscar tutores basados en su ubicación, materias de interés y nivel de educación. Wyzant ofrece una amplia gama de materias, desde matemáticas y ciencias hasta idiomas y música. Los tutores de Wyzant establecen sus propias tarifas y horarios, lo que brinda flexibilidad a los estudiantes para encontrar un tutor que se adapte a sus necesidades y presupuesto.</td>
  </tr>  
  
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Ventajas de los competidores</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Disponibilidad 24/7: Una ventaja clave de Tutor.com es su disponibilidad las 24 horas del día, los 7 días de la semana, lo que permite a los estudiantes acceder a ayuda en cualquier momento, incluso en horarios nocturnos o durante las vacaciones
    Amplia gama de materias: Tutor.com ofrece ayuda en una amplia variedad de materias, desde matemáticas y ciencias hasta idiomas y humanidades, lo que lo hace atractivo para estudiantes de diferentes niveles y áreas de estudio.
    Recursos de aprendizaje adicionales: Además de la tutoría en vivo, Tutor.com ofrece recursos adicionales como ejercicios de práctica y lecciones pregrabadas, lo que proporciona un valor adicional a los estudiantes </td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Selección de tutores personalizada Chegg Tutors permite a los estudiantes buscar y seleccionar tutores basados en sus necesidades específicas, lo que les permite encontrar un tutor que se ajuste a su estilo de aprendizaje y materias de interés
    Sesiones de tutoría en línea en tiempo real: La plataforma ofrece sesiones de tutoría en línea a través de videoconferencia, lo que facilita la interacción en tiempo real con los tutores y la resolución de problemas de manera efectiva
    Expertos en campos específicos: Chegg Tutors se enfoca en proporcionar tutores que son expertos en sus respectivos campos, lo que garantiza una alta calidad de tutoría
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Opciones de tutoría en línea y en persona: Wyzant ofrece la flexibilidad de encontrar tutores tanto en línea como en persona, lo que permite a los estudiantes elegir la modalidad de tutoría que mejor se adapte a sus necesidades y preferencias
    Personalización: Los tutores de Wyzant establecen sus propias tarifas y horarios, lo que brinda a los estudiantes la oportunidad de encontrar un tutor que se ajuste a su presupuesto y horario
    Evaluaciones y reseñas de tutores: Los estudiantes pueden revisar las evaluaciones y reseñas de otros estudiantes sobre los tutores de Wyzant, lo que les ayuda a tomar decisiones informadas sobre a quién elegir
</td>
  </tr>  
  
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Mercado Objetivo</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes de todas las edades: Tutor.com atiende a una amplia variedad de estudiantes, desde escolares hasta universitarios y adultos que buscan mejorar sus habilidades académicas
    Personas que necesitan ayuda inmediata: Su disponibilidad las 24/7 lo hace atractivo para aquellos que necesitan asistencia en cualquier momento, como en la preparación de exámenes de último minuto o la resolución de problemas urgentes
    Aquellos que buscan una amplia gama de materias: Dado que ofrece tutoría en una amplia variedad de materias, atrae a estudiantes de diferentes áreas de estudio.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes universitarios y de nivel superior: Chegg Tutors se enfoca en proporcionar tutores expertos en campos específicos, lo que lo hace especialmente atractivo para estudiantes universitarios y de posgrado que buscan ayuda en materias más avanzadas
    Personas que prefieren tutoría en tiempo real: Aquellos que valoran las sesiones de tutoría en línea en tiempo real a través de videoconferencia pueden encontrar en Chegg Tutors una solución adecuada
    Estudiantes que buscan tutores Especializados: Los estudiantes que necesitan ayuda con materias específicas o desean trabajar con un tutor altamente calificado pueden beneficiarse de Chegg Tutors</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes de todas las edades y niveles: Wyzant ofrece una amplia gama de tutores en línea y locales, lo que lo hace adecuado para estudiantes de todas las edades y niveles educativos, desde primaria hasta posgrado
    Personas que buscan flexibilidad y personalización: Aquellos que desean la flexibilidad de elegir tutores basados en sus necesidades y horarios específicos pueden encontrar en Wyzant una solución conveniente
    Estudiantes que valoran las reseñas y evaluaciones: Wyzant permite a los estudiantes revisar las evaluaciones y reseñas de los tutores, lo que les ayuda a tomar decisiones informadas sobre a quién contratar</td>
  </tr>
    <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estrategias de Marketing</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Publicidad en línea: Utilizar anuncios pagados en motores de búsqueda (SEM) y en redes sociales para llegar a estudiantes que buscan ayuda en línea
    Marketing de contenidos: Crear blogs, artículos y recursos educativos de alta calidad para atraer a estudiantes y posicionarse como una fuente confiable de información y tutoría
    Programas de afiliados: Colaborar con sitios web y blogs relacionados con la educación para promocionar el servicio a cambio de comisiones por referencias
    Ofertas promocionales: Ofrecer descuentos o períodos de prueba gratuitos para atraer a nuevos usuarios y fomentar la retención</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Enfoque en tutores expertos: Destacar la experiencia y calificaciones de los tutores para atraer a estudiantes que buscan asistencia de alta calidad en materias específicas
    Marketing de boca a boca: Incentivar a los estudiantes satisfechos a recomendar el servicio a sus amigos y compañeros de clase
    Contenido educativo: Publicar videos, guías y recursos de aprendizaje en línea para mostrar la experiencia y conocimiento de la plataforma
    Colaboraciones con instituciones educativas: Establecer asociaciones con escuelas y universidades para promover el servicio como un recurso adicional para los estudiantes</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Listados locales y personalizados: Utilizar estrategias de SEO local para destacar en las búsquedas de estudiantes que buscan tutores en su área
    Programa de referencias: Recompensar a los tutores y estudiantes por referir nuevos usuarios a la plataforma
    Marketing de reseñas y testimonios: Mostrar reseñas y testimonios de tutores y estudiantes satisfechos para generar confianza en la plataforma
    Participación en ferias educativas y eventos locales: Promover la plataforma en eventos educativos locales y conferencias para llegar a la comunidad estudiantil
</td>
  </tr>
  </tr>
    <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precios y costos</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: Tutor.com ofrece un servicio de suscripción que generalmente varía desde alrededor de $39.99 a $79.99 por mes, dependiendo del nivel de acceso y la cantidad de tiempo de tutoría en línea incluido en el plan. También ofrecen planes anuales con descuentos
    Costos para la plataforma: Los costos para la plataforma en sí incluyen la compensación para los tutores, el mantenimiento del sitio web y los servidores para brindar tutoría en línea en tiempo real
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: Chegg Tutors utiliza un modelo de precios por hora. El costo por hora de tutoría puede variar según la materia y la experiencia del tutor, pero generalmente oscila entre $30 y $75 por hora
    Costos para la plataforma: Los costos para la plataforma incluyen la compensación para los tutores, los gastos de marketing y publicidad, así como el mantenimiento de la plataforma en línea
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: En Wyzant, los tutores establecen sus propias tarifas, por lo que los precios pueden variar ampliamente. El costo de las lecciones generalmente varía desde $30 hasta $80 o más por hora, dependiendo de la materia y la ubicación del tutor
    Costos para la plataforma: Wyzant cobra una tarifa de servicio a los estudiantes en función del precio de la lección. Además, la plataforma recauda una comisión de los ingresos de los tutores por cada lección
</td>
  </tr>
  
</table>


## 2.1.2 Estrategias y tacticas frente a competidores

a)       Aplicaremos una estrategia de supervisión de los indicadores de desempeño para evaluar el porcentaje de éxito en cada contratación de profesionales para medir las métricas de rendimiento de nuestra aplicación y sugerir cambios para el beneficio del usuario.

b)      La segunda estrategia es desarrollar un ataque en cadena, como estamos inmersos en un ámbito tecnológico, no puedes atacar directamente al competidor más potente, pues cuenta con más medios que nosotros y podría ser contraproducente. Entonces debemos ir obteniendo mayor participación en el mercado atacando los mercados más pequeños y posicionándonos directamente en ellos ofreciendo más modalidades que ellos para que los usuarios prefieran nuestro servicio al de ellos.

c)       Otra estrategia implica la implementación de una interfaz de búsqueda de cursos, de esta manera le permitimos al usuario poder conseguir las clases de ciertas áreas con mayor facilidad separando los cursos en áreas como las de matemáticas, física o comunicaciones para que los usuarios puedan encontrar más fácil algún curso que estén buscando o que quieran aprender y/o reforzar.

d)      Finalmente, emplearemos la estrategia competitiva de diferenciación, consta en ofrecer un producto diferente con una interfaz única y con mejoras totalmente pensadas en la satisfacción del usuario

## 2.2. Entrevistas

En este punto presentaremos los resultados de las entrevistas realizadas a los usuarios objetivos.

## 2.2.1 Diseño de Entrevistas
En esta sección, mostraremos las preguntas que hemos generado para realizar las entrevistas a los dos tipos de usuarios objetivos. Cabe destacar, que las preguntas realizadas son de tipo abierto, con el objetivo de recolectar información relevante que nos ayude a tener una idea más precisa de cómo solucionar problemas de nuestros usuarios objetivo.
Preguntas principales y complementarias para las entrevistas
1.       Estudiantes
a.       Preguntas Principales:

·         ¿Cuáles son los principales motivos por los que usted usaría el servicio de asesoramiento?

·         ¿Cuál o cuáles son los problemas que mayor dificultad tiene a la hora de aprender?

·         ¿Ha contratado alguna vez algún profesor particular para poder ayudarlo con sus estudios?

·         ¿Qué opinas de una web donde puedes encontrar asesores para poder aprender los temas que se te dificultan?

b.       Preguntas complementarias

·         ¿Cuántos años tiene?

·         ¿En qué ciclo esta?

·         ¿Cuántas horas al día estudia?

·         ¿Cuáles son los cursos que mejor se te dan?

·         ¿Usas algún método para estudiar o solo apuntes y grabaciones?

·         ¿Te cuesta aprender los temas que se enseñan en las clases?
 
2.       Asesores
a.       Preguntas Principales

·         ¿ya ha dictado clases particulares antes?

·         ¿Cuántos años de experiencia tiene en su ámbito laboral?

·         ¿Considera difícil el dictado de clases particulares?

·         ¿Qué características le gustaría que tuviera nuestra 
aplicacion?
·         ¿Qué opina de que usted pueda poner su tarifa por sus servicios?

·         ¿Considera una ventaja para usted que luego de sus servicios sus estudiantes puedan ponerle calificación por su trabajo?

.	¿Cree que sería más ordenado el tener un horario impuesto por usted, para que los estudiantes separen su tiempo?

b.       Preguntas complementarias

·         ¿Cuántos años tiene?

·         ¿Cuál es su ocupación?

·         ¿Cuál es su estado civil?

·         ¿Cuáles son los dispositivos que más usa para comunicarse?

.	¿Qué curso has enseñado?

# 2.2.2 Entrevistas 
.Entrevistado 1:

.Nombres y Apellidos: Alexis Frogoziolo Lujan

.Edad: 26 años

.Distrito: Comas

.Evidencia de la reunión:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149191053199556688/image.png" alt="" width="500" height="200" />

●	Url de stream:

●	Timing y duración: 

●	Resumen sobre la entrevista:

La entrevista fue realizada a Alexis Frogoziolo, tiene 26 años y reside en Comas. Es un backend developer, el cual en sus tiempos libres cumple la labor de tutor de programación para jóvenes y niños, la cual cumple desde hace 2 años. El siente que no hay mucha dificultad en la interacción con los alumnos, debido a que son pocos alumnos, pero a más cantidad más dificultad. Después de explicarle nuestra startup, a él le gustaría tener una apartado para mostrar sus logros y especialidades. Asimismo, ve acierto tener la posibilidad de poner una tarifa él mismo. De la misma manera, encuentra satisfactorio el tener un feedback sobre sus clases.

Entrevistado 2:

●	Nombres y Apellidos: Dora Villalobos

●	Edad: 51 Años

●	Distrito: Surco

●	Evidencia de la reunión

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192195623092365/image.png" alt="" width="500" height="250" />

●	Url del Stream:

●	Timing y duracion: 5:33

●	Resumen de la entrevista

La entrevista fue realizada a  Dora Villalobos, tiene 51 años y reside en surco. Es una arquitecta con varios años de experiencia en el campo laboral, trabaja para la municipalidad de surco. Ha tenido experiencia capacitando a otras personas en el ámbito de la arquitectura pero no con alumnos. Luego de explicarle lo que hace nuestra startup le interesó el tema y dice que le gustaría poder experimentar lo que es dar asesorías a alumnos que lo requieran, le parece adecuado y perfecto que una de las características de la app sea que luego de las asesorías los alumnos puedan dar un feedback sobre qué es lo que les pareció la sesión dándoles una calificación.

Entrevistado 3:

●	Nombres y Apellidos: Alex Herrera

●	Edad: 21 Años

●	Distrito: Chorrillos

●	Evidencia de la reunión


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192233686417539/image.png" alt="" width="600" height="250" />

●	Url del Stream: https://youtu.be/PLsGASh4hF0?si=7r3B4JQQjxkKqrvP 

●	Timing y duración: 3:35

●	Resumen de la entrevista:

Entrevista 4:

●	Nombres y Apellidos: Carlos Martinez

●	Edad: 20

●	Distrito: Lima

●	Evidencia de la reunión:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192262153158676/image.png" alt="" width="600" height="250" />

●	Url del Stream: https://youtu.be/xpjy7Ydvpe0

●	Timing y duración: 4 minutos.

●	Resumen de la entrevista: El estudiante Carlos nos cuenta un poco de él y muestra interés sobre nuestro proyecto de ayuda para los estudiantes. Además, le preguntamos porqué es necesario tener ayuda en los temas que no logra entender.

Entrevistado 5:

●	Nombres y Apellidos: Liz Ramos

●	Edad: 30 Años

●	Provincia: La Plata

●	Evidencia de la reunión

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192287943925780/image.png" alt="" width="350" height="" />

●	Url del stream: https://youtu.be/sfhP7M2MDk8

●	Timing y duración: 11 minutos

●	Resumen de la entrevista: 
Liz nos cuenta de su experiencia como asesora en fotografía, considera que las enseñanzas que se brindan en la aplicación web debe tener asesorías en tiempo real para que el estudiante pueda resolver sus dudas y el asesor le brinde retroalimentación. Así mismo le gustaría que existan foros de estudiantes para poder compartir ideas y dudas. Por otro lado, considera que la calificación de docentes genera competitividad en la plataforma y con esto un mejor desempeño en el servicio que brindan.

## 2.2.3 Analisis de Entrevistas
A continuación, se desarrolla una estrategia en conjunto con el equipo para identificar los puntos en común en base a las respuestas de cada entrevistado a cada pregunta. Esto nos ayuda a realizar un análisis más conciso y seguro para desarrollar nuestra aplicación en base a la información recolectada. 

**Segmento 1: Estudiantes que buscan Ayuda en sus estudios**

¿Cuáles son los principales motivos por los que usted usaría el servicio de asesoramiento?

El 80% de los estudiantes mencionó razones para usar el servicio de asesoramiento, como superar dificultades en el aprendizaje, mejorar su rendimiento académico y obtener ayuda específica en temas problemáticos.

¿Cuál o cuáles son los problemas que mayor dificultad tiene a la hora de aprender?

El 90% de los estudiantes identificó problemas específicos que les resultan difíciles al aprender, lo que resalta la necesidad de asistencia personalizada.

¿Ha contratado alguna vez algún profesor particular para poder ayudarlo con sus estudios?

El 40% de los estudiantes ha contratado profesores particulares en el pasado, lo que demuestra su disposición a buscar ayuda externa.

¿Qué opinas de una web donde puedes encontrar asesores para poder aprender los temas que se te dificultan?

El 100% de los estudiantes expresó interés en una plataforma donde puedan encontrar asesores para abordar temas problemáticos, lo que respalda la propuesta del proyecto.

¿Usas algún método para estudiar o solo apuntes y grabaciones?

El 70% de los estudiantes compartió sus métodos de estudio, lo que puede ayudar a diseñar recursos y funcionalidades que se ajusten a sus preferencias de aprendizaje.

¿Te cuesta aprender los temas que se enseñan en las clases?

El 80% de los estudiantes admitió dificultades para aprender algunos temas en las clases, lo que subraya la necesidad de apoyo adicional.

¿Qué opinas de este proyecto?

El 90% de los estudiantes expresó una opinión positiva sobre el proyecto, lo que indica un fuerte interés en la plataforma propuesta.

¿Qué funcionalidades adicionales que creas conveniente nos recomiendas agregar?

Los estudiantes proporcionaron recomendaciones variadas para funcionalidades adicionales, lo que podría influir en el diseño de la plataforma.

**Segmento 2: Asesores**

¿Ya ha dictado clases particulares antes?

El 60% de los asesores tiene experiencia previa en la enseñanza, lo que sugiere su capacidad para brindar asesoramiento.

¿Cuántos años de experiencia tiene en su ámbito laboral?

Los asesores cuentan en su mayoría con años de experiencia laboral, lo que puede aumentar su credibilidad ante los estudiantes.


El 70% de los asesores percibe cierta dificultad en el dictado de clases particulares, lo que resalta la importancia de herramientas que simplifiquen este proceso.

¿Qué características le gustaría que tuviera nuestra aplicación?

Los asesores compartieron sus expectativas sobre las características de la aplicación, lo que puede guiar el desarrollo de la plataforma.

¿Qué opina de que usted pueda poner su tarifa por sus servicios?

El 90% de los asesores ve favorable la posibilidad de fijar sus tarifas, lo que puede ser un incentivo para unirse a la plataforma.

¿Considera una ventaja para usted que luego de sus servicios sus estudiantes puedan ponerle calificación por su trabajo?

El 80% de los asesores considera una ventaja ser evaluado por los estudiantes, lo que podría mejorar la calidad del servicio.

¿Cree que sería más ordenado el tener un horario impuesto por usted, para que los estudiantes separen su tiempo?

El 60% de los asesores ve ventajas en establecer horarios, lo que puede ayudar a la organización y planificación.

¿Cuáles son los dispositivos que más usa para comunicarse?

Los asesores mencionaron los dispositivos que utilizan para comunicarse, lo que puede informar las opciones de comunicación en la plataforma.

¿Qué curso has enseñado?

Los asesores compartieron información sobre los cursos que han enseñado, lo que puede ser útil para el emparejamiento con estudiantes.

**Conclusiones de los análisis de la entrevistas:**

El análisis muestra un gran interés por parte de los estudiantes en buscar asesores para superar dificultades específicas en el aprendizaje. La mayoría de los asesores tienen experiencia laboral y están dispuestos a ofrecer sus servicios. La plataforma propuesta tiene el potencial de satisfacer estas necesidades, pero debe incluir características que faciliten la conexión entre los estudiantes y los asesores. La posibilidad de que los asesores establezcan sus tarifas y sean evaluados por los estudiantes es vista de manera positiva. Además, la plataforma puede proporcionar herramientas de organización, como horarios, para una experiencia más eficiente.

## 2.3 NeedFinding
## 2.3.1 User Personas

A continuación, se construirán los User Persona de cada segmento objetivo de nuestra plataforma. Para ello, se utilizarán los datos recolectados de las entrevistas realizadas; principalmente, los que muestran los objetivos, motivaciones y frustraciones con las que cuentan cada uno de los sectores que conforman al público al que va dirigida la aplicación. Es decir, se presentará un estereotipo de un estudiante como de un asesor.

**User Persona- Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192370945011712/image.png" alt="" width="400" height="" />

**User Persona- Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149195290138660874/image.png" alt="" width="400" height="" />

## 2.3.2 User Task Matrix 
En esta etapa nos enfocaremos en las tareas que los User Personas Estudiantes, representados por Mateo Aguirre. Asimismo, el segundo User Persona son los profesionales que dan las asesorías de los cursos, representados por Carlos Mendéz. realizan para alcanzar su propósito, teniendo como segmentos objetivos a los estudiantes jóvenes que quieran mejorar en su vida académica como los asesores que quieren generar un ingreso extra realizando estas asesorías

<table>
<tr>
    <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">User Task Matrix</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;" colspan="2">Mateo Aguirre</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;" colspan="2">Carlos Mendez</th>
</tr>

  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Frecuencia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Importancia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Frecuencia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Importancia</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Registrarse</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Iniciar Sesion</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Buscar Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Ver Perfil de Asesores</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Programar una Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Participar en una Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Evaluar una asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Actualizar Perfil</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
  </tr>
</table>
Tareas con mayor frecuencia e importancia: 

• Frecuencia: Las tareas con mayor frecuencia son aquellas relacionadas con el funcionamiento de la aplicación acciones como registrarse e iniciar sesión en la plataforma son las que más se realizan así como también el participar en una asesoría es una acción que es la que más se realizaría.

• Importancia: Como Tareas de mayor importancia son aquellas que son esenciales para que la plataforma pueda cumplir la función tareas como las de Buscar una asesoría son de las más importantes ya que la plataforma se base en eso otras acciones con una importancia importante son la de programar una sesión de asesoría ya que aquí es donde se decide cuando es que se va a llevar a cabo como el tema o el trabajo a tratar durante la asesoría como el tiempo y el pago de la asesoría 

Diferencias y Similitudes:
La principal diferencia entre los asesores y los estudiantes es que los que van a buscar son los estudiantes principalmente ya que ellos son los que van a escoger con quién quieren tener una asesoria otra diferencia es que a la hora de evaluar, esta sería una función pensada más para los estudiantes que para los asesores ya que aquí pueden decir si el asesor cunmplio con las expectativas y como se sintio en general con la asesoría. Y una similitud que tiene es a la hora de coordinar una asesoría ya que los dos se juntaran para decidir todo lo esencial para poder llevar a cabo la asesoría. 

## 2.3.3 User Journey Mapping
El User Journey Mapping es una herramienta de Design Thinking que nos ayuda a graficar un mapa con las etapas, canales, elementos e interacciones por las que pasa nuestro usuario durante el ciclo de uso del servicio. 

**Segmento 1-Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196650934456420/image.png" alt="" width="400" height="" />

**Segmento 2-Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196689094230157/image.png" alt="" width="400" height="" />

## 2.3.4 Empathy Mapping

En esta sección se presenta el Empathy Mapping de nuestros 2 segmentos objetivos. Esta herramienta se utilizó porque permite identificar nuestro público objetivo, conocer su entorno y sus necesidades, lo cual nos permite ver el mundo a través de su perspectiva.

**Segmento 1 : Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196720085946480/image.png" alt="" width="400" height="" />

**Segmento 2-Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196760254783488/image.png" alt="" width="400" height="" />

## 2.3.5 As-is Scenario Mapping
En esta sección, se identificó las fases que podría presentar a nuestros User persona, del cómo se afrontó, sus pensamientos, sus sentimientos para identificar qué soluciones son las más adecuadas para satisfacer sus inquietudes.


## Segmento 1- Estudiantes que requieren una asesoria

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149486010699362396/C72rYIXdaZDc1BP7utev1LrNJ5Zs3g8DKSRVOUJsxF89fsSzOvwTRwMpvse-MZuot-M_d3ToQ_6zHu4Y5SoVY4IYXzfUV0uC1ip8iZQR-irMKtH6UKRvtgniaLP2XfxN75jdhxoH1nCV9teBep_h3ik.png" alt="" width="" height="" />

## Segmento 2- Asesores 


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149488074343055441/image.png" alt="" width="" height="" />

# Chapter 03: REQUIREMENTS SPECIFICATION
## 3.1. To-Be Scenario Mapping
## 3.1.1 Segmento Estudiante:
<img src="https://cdn.discordapp.com/attachments/1143747947322941440/1149837196380098620/Blank_board_2.png" alt="" width="" height="" />

## 3.1.2 Segmento Asesor:

<img src="https://cdn.discordapp.com/attachments/1143747947322941440/1149835913585762394/Blank_board_3.png" alt="" width="" height="" />

## 3.2. User Stories:
### User Story: US01

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US01 </b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante</td>
    <td>Titulo:</td>
    <td>Búsqueda de asesores</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como estudiante, quiero buscar asesores disponibles para estudiar el curso que necesito.</td>
  </tr>

  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Búsqueda Exitosa
    Dado que soy un estudiante registrado en la plataforma.
    y he iniciado sesión,
    Cuando ingresó a la página de búsqueda de asesores.
    Entonces, debo ver un formulario de búsqueda que incluya campos para seleccionar la materia deseada.

    Escenario 02: Búsqueda sin Resultados

    Dado que soy un estudiante registrado en la plataforma.
    y he iniciado sesión.
    Cuando ingresó a la página de búsqueda de asesores.
    Entonces, debo ver un formulario de búsqueda que incluya campos para seleccionar la materia deseada.
    Y no encuentra resultados de asesores en este caso. 
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Alta</td>
  </tr>
  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">6 horas</td>
  </tr>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US02 </b> </td>
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Asesor</td>
    <td>Titulo:</td>
    <td>Recibir notificaciones de solicitudes</td>
  </tr>
  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como asesor, quiero recibir notificaciones para que un estudiante me envíe una solicitud de tutoría.</td>
  </tr>
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Notificación Exitosa

    Dado que soy un tutor registrado en la plataforma 
    y he iniciado sesión,
    Cuando un estudiante me envía una solicitud de tutoría.
    Entonces, debo recibir una notificación en tiempo real en la aplicación que indique que tengo una nueva solicitud.
    Además, debo recibir un correo electrónico de notificación sobre la nueva solicitud.

    Escenario 02: Sin Notificación

    Dado que soy un tutor registrado en la plataforma 
    y he iniciado sesión,
    Cuando un estudiante me envía una solicitud de tutoría,
    Entonces, si no estoy en línea en ese momento,
    Debo recibir un correo electrónico de notificación sobre la nueva solicitud sin leer.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Media</td>
  </tr>
  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">4 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US03 </b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante</td>
    <td>Titulo:</td>
    <td>Reserva de tutoría</td>
  </tr>
  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como estudiante, quiero reservar sesiones de tutoría con los asesores seleccionados para recibir confirmaciones de reserva.</td>
  </tr>
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Reserva Exitosa

    Dado que soy un estudiante registrado en la plataforma 
    y he iniciado sesión,
    Cuando encuentro un asesor adecuado 
    y hago clic en "Reservar sesión",
    Entonces, debo poder seleccionar una fecha y hora disponibles en el calendario del asesor.
    Cuando selecciono una fecha y hora y confirmó la reserva,
    Debo recibir una confirmación inmediata en la aplicación que indique que la reserva fue exitosa.

    Escenario 2 - Reserva Cancelada

    Dado que soy un estudiante registrado en la plataforma 
    y he iniciado sesión,
    Cuando hago una reserva de sesión con un asesor,
    Entonces, si necesito cancelar la reserva antes de la fecha programada,
    Y tener la opción de cancelar la reserva.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Alta</td>
  </tr>
  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">6 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US04 </b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Asesor</td>
    <td>Titulo:</td>
    <td>Pago a los asesores</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como asesor, quiero recibir pagos de manera segura por las sesiones de tutoría que he realizado.</td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Pago Exitoso

    Dado que soy un tutor registrado en la plataforma 
    y he iniciado sesión,
    Cuando un estudiante reserva y completa una sesión de tutoría conmigo,
    Entonces, el sistema debe procesar el pago de manera automática y segura utilizando un método de pago registrado por el estudiante.
    Debo recibir una notificación de confirmación de pago una vez que se complete con éxito.

    Escenario 02: Pagó con Problemas

    Dado que soy un asesor registrado en la plataforma y he iniciado sesión,
    Cuando un estudiante reserva 
    y completa una sesión de tutoría conmigo,
    Entonces, si hay algún problema con el procesamiento del pago (por ejemplo, tarjeta de crédito rechazada),
    Debo recibir una notificación que describa el problema y proporcione instrucciones sobre cómo solucionarlo.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Media</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">5 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US05</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Asesor</td>
    <td>Titulo:</td>
    <td>Configuración de cursos</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como asesor, quiero especificar los cursos para enseñar y mis horarios de disponibilidad.</td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Configuración Exitosa

    Dado que soy un asesor registrado en la plataforma 
    y he iniciado sesión,
    Cuando accedo a mi perfil de tutor,
    Entonces, debo tener una sección de "Materias que Enseño" donde puedo seleccionar las materias que estoy dispuesto a enseñar.
    Debe poder establecer mis horarios de disponibilidad en un calendario y marcar los bloques de tiempo en los que estoy disponible para sesiones de tutoría.

    Escenario 02: Sin Materias ni Horarios Configurados

    Dado que soy un asesor registrado en la plataforma
    Y he iniciado sesión,
    Cuando accedo a mi perfil de tutor,
    Entonces, si no he especificado las materias que enseño ni mis horarios de disponibilidad,
    Debo ver un mensaje que me indique que necesito completar mi perfil para aparecer en las búsquedas de estudiantes.
    Y recibir recordatorios y sugerencias para completar esta información.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Alta</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">6 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US06</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante</td>
    <td>Titulo:</td>
    <td>Historial de sesiones y comentarios</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como estudiante, quiero tener un historial de mis sesiones de tutoría anteriores para la opción de dejar comentarios y calificaciones.

</td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Historial y Calificaciones Exitosos

    Dado que soy un estudiante registrado en la plataforma 
    y he iniciado sesión,
    Cuando accedo a mi perfil,Entonces, debo tener una sección de "Historial de Sesiones" que muestre todas las sesiones de tutoría que he completado.
    Debo tener la opción de dejar una calificación (por ejemplo, de 1 a 5 estrellas) y un comentario después de cada sesión.
    Y mis calificaciones y comentarios deben estar visibles en el perfil del tutor correspondiente.

    Escenario 02: Sin Calificaciones y Comentarios

    Dado que soy un estudiante registrado en la plataforma 
    y he iniciado sesión,
    Cuando accedo a mi perfil,
    Entonces, si no he completado ninguna sesión de tutoría,
    Debo ver un mensaje que indique que mi historial de sesiones está vacío.
    
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Media</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">6 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US07</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante/Tutor</td>
    <td>Titulo:</td>
    <td>Traslado en la landing page</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como estudiante, quiero tener un historial de mis sesiones de tutoría anteriores para la opción de dejar comentarios y calificaciones.

</td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Selección de opciones del menú de traslación

    Dado que el usuario se encuentra en el 
    Landing Page
    Cuando clickee en HOME
    Entonces se traslada al inicio de la página
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Baja</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">3 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US08</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante/Tutor</td>
    <td>Titulo:</td>
    <td>Direccionamiento a la aplicación web</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como usuario, quiero tener una opción para poder ingresar a la página web por medio de la landing page.
  </td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Ingreso desde el buscador

    Dado que el usuario se encuentra en un 
    navegador
    Cuando ingrese en el buscador StudyMentor 
    Entonces podrá acceder a la aplicación web

    Escenario 02: Ingreso desde el Menú de Inicio

    Dado que el usuario se encuentra en la landing page
    Cuando presiona el botón de descargar app web
    Entonces se dirigirá a la aplicación web
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Baja</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">2 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US09</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante/Tutor</td>
    <td>Titulo:</td>
    <td>Registro de cuenta</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como usuario, quiero tener la capacidad de crear una nueva cuenta para ingresar a la plataforma.
  </td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Ingreso correcto de datos

    Dado que el usuario se encuentra con el formulario para registrarse
    Cuando ingresa sus credenciales correctamente
    Entonces se registra una nueva cuenta

    Escenario 02: Ingreso incorrecto de datos

    Dado que el usuario se encuentra en el 
    formulario para registrarse
    Cuando ingresa sus credenciales 
    incorrectamente
    Entonces no podrá registrarse y tendrá que cambiar las credenciales incorrectas.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Media</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">1 hora</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US10</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante/Tutor</td>
    <td>Titulo:</td>
    <td>Inicio de sesión</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como usuario, quiero tener la capacidad de ingresar a la plataforma con mi cuenta creada para tener mis credenciales guardadas.
  </td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Ingreso correcto de datos

    Dado que el usuario ya registró su cuenta
    Cuando ingresa sus credenciales correctamente
    Entonces ingresa a la plataforma.

    Escenario 02: Ingreso incorrecto de datos

    Dado que el usuario ya registró su cuenta anteriormente
    Cuando ingresa sus credenciales 
    incorrectamente
    Entonces no podrá ingresar a la plataforma
    Y tendrá que digitar correctamente sus credenciales
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Media</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">2 horas</td>
  </tr>
</table>

</table>

  <table>
  <tr>
    <td style = "text-align:center;" colspan="4">User Story: US11</b> </td>
    
  </tr>
  <tr>
    <td>Usuario:</td>
    <td>Estudiante/Tutor</td>
    <td>Titulo:</td>
    <td>Visualización de la landing page</td>
  </tr>

  <tr>
    <td colspan="2">Descripcion:</td>
    <td colspan="2">Como usuario, quiero que se visualice los servicios de la plataforma  para poder conocer más sobre la aplicación.
  </td>
  </tr>
  
  <tr>
    <td style = "text-align:center;" colspan="2">Criterios de aceptación</td>
    <td colspan="2">

    Escenario 01: Vista de secciones

    Dado que el usuario se encuentra en el 
    Landing Page
    Cuando quiera saber sobre los servicios que ofrecemos
    Entonces se traslada a la sección de Servicios.
  </td>
  </tr>
  <tr>
    <td colspan="2">Prioridad</td>
    <td colspan="2">Baja</td>
  </tr>

  <tr>
    <td colspan="2">Tiempo estimado</td>
    <td colspan="2">3 horas</td>
  </tr>
</table>

## 3.3. Impact Mapping

<img src="https://cdn.discordapp.com/attachments/1143747947322941440/1149842997651968061/Untitled_5.jpg" alt="" width="" height="" />

## 3.4. Product Backlog

<table>
  <tr>
    <th>#Orden</th>
    <th>User Story ID</th>
    <th>Titulo</th>
    <th>Descripcion</th>
    <th>Story Points (1/2/3/4/5/8)</th>
  </tr>
  <tr>
    <td>1</td>
    <td>US01</td>
    <td>Búsqueda de asesores</td>
    <td>Como estudiante, quiero buscar asesores disponibles para estudiar el curso que necesito.</td>
    <td>8</td>
  </tr>
  
  <tr>
    <td>2</td>
    <td>US02</td>
    <td>Recibir notificaciones de solicitudes</td>
    <td>Como asesor, quiero recibir notificaciones para que un estudiante me envíe una solicitud de tutoría.</td>
    <td>5</td>
  </tr>

  <tr>
    <td>3</td>
    <td>US03</td>
    <td>Reserva de tutoría</td>
    <td>Como estudiante, quiero reservar sesiones de tutoría con los asesores seleccionados para recibir confirmaciones de reserva.</td>
    <td>8</td>
  </tr>

  <tr>
    <td>4</td>
    <td>US04</td>
    <td>Pago a los asesores</td>
    <td>Como asesor, quiero recibir pagos de manera segura por las sesiones de tutoría que he realizado.</td>
    <td>5</td>
  </tr>
  
  <tr>
    <td>5</td>
    <td>US05</td>
    <td>Configuración de cursos</td>
    <td>Como asesor, quiero especificar los cursos para enseñar y mis horarios de disponibilidad.</td>
    <td>8</td>
  </tr>

  <tr>
    <td>6</td>
    <td>US06</td>
    <td>Historial de sesiones y comentarios</td>
    <td>Como estudiante, quiero tener un historial de mis sesiones de tutoría anteriores para la opción de dejar comentarios y calificaciones.</td>
    <td>5</td>
  </tr>

  <tr>
    <td>7</td>
    <td>US07</td>
    <td>Traslado en la landing page</td>
    <td>Como usuario, quiero tener una opción para poder trasladarme en la landing page</td>
    <td>5</td>
  </tr>

  <tr>
    <td>8</td>
    <td>US08</td>
    <td>Direccionamiento a la aplicación web</td>
    <td>Como usuario, quiero tener una opción para poder ingresar a la página web por medio de la landing page</td>
    <td>3</td>
  </tr>

  <tr>
    <td>9</td>
    <td>US09</td>
    <td>Registro de cuenta</td>
    <td>Como usuario, quiero tener la capacidad de crear una nueva cuenta para ingresar a la plataforma</td>
    <td>5</td>
  </tr>

  <tr>
    <td>10</td>
    <td>US10</td>
    <td>Inicio de sesión</td>
    <td>Como usuario, quiero tener la capacidad de ingresar a la plataforma con mi cuenta creada para tener mis credenciales guardadas.</td>
    <td>5</td>
  </tr>

  <tr>
    <td>11</td>
    <td>US11</td>
    <td>Visualización de la landing page</td>
    <td>Como usuario, quiero que se visualicen los servicios de la plataforma  para poder conocer más sobre la aplicación.</td>
    <td>5</td>
  </tr

</table>

# Capitulo 4: Product Design
## 4.1 Style Guidelines
En esta sección, se establecen las pautas de estilo y desarrollo coherentes para garantizar que la solución "StudyMentor" tenga un enfoque unificado y consistente en su implementación.
### 4.1.1 General Style Guidelines
#### Brand Overview
La atención integral y efectiva a estudiantes universitarios que enfrentan desafíos académicos se vuelve esencial en nuestra sociedad. Las necesidades de los estudiantes requieren un enfoque especializado, por lo que nuestra solución, "StudyMentor", surge como respuesta a la necesidad de asesoría en el ámbito educativo. Ofrecemos acceso virtual a profesionales y especialistas en diversos cursos, asegurando una calidad excepcional en la asesoría. Tenemos conocimiento que la atención personalizada es crucial en la educación para el éxito académico. Con "StudyMentor", estamos comprometidos en brindar un entorno donde los estudiantes puedan obtener la ayuda necesaria para comprender los temas, prepararse para exámenes y desarrollar habilidades. Nuestra visión es ser la plataforma líder para estudiantes que buscan mejorar su rendimiento académico y alcanzar sus objetivos educativos.

#### Brand Name
El software ha sido bautizado como "StudyMentor". Este nombre surge directamente de nuestra visión de proporcionar orientación académica especializada y personalizada a estudiantes universitarios. Al optar por el idioma inglés, hemos buscado crear una identidad amigable y atractiva para nuestros usuarios potenciales. La palabra "StudyMentor" fusiona perfectamente el acto de estudiar y el concepto de guía, transmitiendo la idea de un mentor que brinda dirección y apoyo en el ámbito educativo. Nuestra esperanza es que este nombre se convierta en sinónimo de excelencia educativa y se asocie con una herramienta confiable para el crecimiento y el éxito académico.
A continuación, se presenta el logo o marca de nuestra solución propuesta.

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149748578630242434/image.png" alt="icons">

#### Typography
La selección de tipografías resulta esencial para dar forma y orden al aspecto visual de todas las plataformas que se crearán con el fin de satisfacer las características fundamentales de la aplicación. Se ha considerado primordial que las fuentes sean fácilmente legibles y contribuyan a la experiencia del usuario, por lo cual se han escogido estos estilos de letras con especial atención.

<table>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Francois One Google Fonts</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Roboto Google Fonts</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Lato
Google Fonts
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Inter
Google Fonts
</td>
  </tr>
</table>

# Head

<table>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Name</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Font size</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Line Height</tr>
     <tr>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h1>Heading 1</h1></td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">56 px</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">61.6 px</td>
</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h2>Heading 2</h2></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">48 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">52.8 PX</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h3>Heading 3</h3></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Font size</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Line Height</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h4>Heading 4</h4></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">32 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">35.2 px</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h5>Heading 5</h5></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">24 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">26.4 px</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h6>Heading 6</h6></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">20 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">22 px</tr>
</table>

#### Colors
<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149748786747424849/image.png" alt="colors">

#### Spacing
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149510151909412864/image.png" alt="spacing">

### 4.1.2 Web Style Guidelines
Daremos forma a una aplicación que se adapte a cualquier dispositivo tecnológico, asegurando que el diseño del contenido no se vea afectado. Por consiguiente, consideraremos cada tipo de dispositivo para organizar el contenido de manera óptima en cada caso.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149510537466626048/disenCC83o20responsive-1.png" alt="responsive-image" width="300" height="200" style="border-radius: 25%;">

Aplicaremos el patrón Z en nuestra interfaz, lo que permitirá destacar nuestro logo o marca en la esquina superior izquierda, marcando el inicio de la interacción del usuario. Luego, el recorrido se desplazará hacia la derecha, revelando las diversas opciones disponibles como "Acerca de", "Reserva tu sesión" o el área de configuración. Enseguida, el usuario se desplazará verticalmente hacia abajo, continuando su interacción con el contenido de la aplicación. Finalmente, la trayectoria lo llevará a la esquina inferior derecha, donde podrá acceder a nuestras redes sociales y medios de contacto.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149511335265194034/eyetrackingpatronz.png" alt="z-pattern" width="300" height="230" style="border-radius: 25%;">

Consecuentemente, el diseño de nuestra aplicación incorporará colores que inspiren al usuario a explorar la plataforma con entusiasmo. También implementaremos sombras y espacios adecuados para mejorar la legibilidad de la información y para mantener el contenido en un formato que no abrume al navegante. Utilizaremos varios de los siguientes elementos en el diseño para lograr estos objetivos.
Se emplearán algunos de los siguientes elementos:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149511726430158888/image.png" alt="selection-box-and-buttons" >

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149512062825938954/image.png" alt="big-elements" >

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149512103393247252/image.png" alt="cards" >

Link para visualizar el figma con el Style Guidelines general:
https://www.figma.com/file/8UXIDwaQ0ClCHsdiF5Yt9J/Web-%26-Mobile-Style-Guidelines-(StudyMentor)?type=design&node-id=0%3A1&mode=design&t=04Xp0QWvdfrdRq9v-1

## 4.2 Information Architecture
En esta sección, detallaremos la estructura de nuestra solución "StudyMentor" para satisfacer las necesidades de nuestros usuarios. Abordaremos varios aspectos que permitirán a los estudiantes organizar y acceder al contenido de manera eficiente: Sistemas de Organización, Sistemas de Etiquetado, Etiquetas de SEO y Metaetiquetas, Sistemas de Búsqueda y Sistemas de Navegación
### 4.2.1 Organization Systems
En las siguientes líneas, describiremos cómo se implementarán diferentes métodos de organización visual para cada uno de nuestros segmentos de usuarios, asegurándonos de que el contenido esté estructurado de manera coherente y accesible.

### Segmento 1: Estudiantes que buscan Ayuda en sus estudios:

#### Jerárquica:

#### Materias y Cursos:
- Los estudiantes podrán acceder a diferentes materias y cursos disponibles. La información se organizará por categorías de materias y secciones, permitiendo a los estudiantes explorar y elegir áreas de interés.

#### Asesores y Profesores:
- Se mostrará una lista de asesores y profesores disponibles en cada materia. La organización se realizará en función de la especialidad y la experiencia de cada asesor.

#### Sesiones de Asesoría:
- Los estudiantes podrán programar sesiones de asesoría con sus profesores y asesores elegidos. Las fechas y horarios se mostrarán en orden cronológico.

#### Perfil del profesional:
- El usuario podrá acceder al perfil del profesional para hacer una selección de preferencia más íntegra. Los datos del profesional estarán organizados de acuerdo con su relevancia.

#### Sesiones de Asesoría:
- Los estudiantes podrán programar sesiones de asesoría con sus profesores y asesores elegidos. Las fechas y horarios se mostrarán en orden cronológico.

### Secuencial:

#### Programación de Sesiones:
 Los estudiantes seguirán pasos para programar una sesión de asesoría. Esto incluirá la selección de un asesor, elección de fecha y hora, y confirmación de la reserva.
 

## Segmento 2: Profesores y Asesores: 

### Jerárquica:

#### Lista de Estudiantes: 
 - Los profesores verán una lista de estudiantes que han solicitado asesoría. La información se organizará en función de las fechas de solicitud.

#### Sesiones Programadas:
- Los profesores accederán a sus sesiones programadas, organizadas por fechas y horarios.

#### Perfil del estudiante: 
- El profesional podrá acceder al perfil del estudiante para revisar que está solicitando. Esta información estará organizada de acuerdo con su relevancia.

#### Contenido de Asesoría:
- Los recursos y materiales que los profesores comparten con los estudiantes se organizarán por temas y categorías.

Es importante destacar que hay características compartidas por ambos grupos de usuarios, que incluyen lo siguiente:

**Jerárquica:**

- **Landing Page:** En esta sección, presentaremos información esencial de nuestro proyecto para cualquier interesado. Esto abarcará detalles sobre nuestros servicios y nuestra información de contacto, entre otros aspectos. Esta información se estructurará de manera que lo más relevante aparezca en primer lugar y se organizará en categorías temáticas.

- **Reseñas:** En esta sección, los usuarios tendrán la oportunidad de evaluar la calidad del servicio brindado por profesionales o asesores. Estas evaluaciones se organizarán cronológicamente (las opiniones más recientes se mostrarán primero).

**Matricial:**

- **Menú de opciones:** Ambos segmentos tendrán acceso a un menú principal desde donde podrán acceder a las funciones necesarias, organizadas por categorías.

- **Noticias y Recomendaciones:** Ambos segmentos encontrarán noticias y recomendaciones organizadas en base a temas.

Esta arquitectura de información optimizará la experiencia del usuario, facilitando la exploración y el acceso a recursos relevantes para cada segmento de usuarios en nuestra plataforma "StudyMentor".

### 4.2.2 Labeling Systems

A continuación, presentaremos el sistema de categorización que permitirá a nuestros visitantes acceder a la información de nuestra landing page mediante una única palabra.

Tenemos cuatro “headings” con una fuente sans-serif ubicadas en la parte superior de la Landing page:

- **Home:** La sección preseleccionada en la que los usuarios encontrarán la información más importante, diseñada para llamar su atención.

- **About:** La sección en la que los clientes pueden conocer nuestra misión, visión, identidad y actividades.

- **Services:** Una sección dedicada a enumerar y describir los servicios que proporcionamos.

- **Contact:** La sección donde se proporciona información detallada sobre nuestros canales de comunicación y ubicación.

Para la versión de la Web Aplication dirigida a estudiantes de Arquitectura, disponemos de cinco “headings” con fuente  Lato, ubicados en el menú principal de la parte izquierda.

- **Home** Área predeterminada donde se presentan noticias de alta relevancia junto con las opciones clave dirigidas al estudiante.

- **My profile:** Sección donde los datos personales del estudiante están disponibles.

- **News:** Espacio donde el estudiante puede ver noticias relacionadas con los cursos de Arquitectura.

- **Prescription:** Zona donde el estudiante puede revisar todas las prescripciones que ha recibido hasta ahora.

- **Configuration:** Sección donde el estudiante puede ajustar la configuración por defecto de la plataforma.

Para la Web Application dirigida a asesores, tenemos cinco "headings" con fuente Lato ubicados en el menú principal en el lateral izquierdo.

- **Home:** Sección predeterminada donde se presentan noticias relevantes junto con las opciones clave dirigidas al profesional o asesor.

- **My profile:** Sección donde se encuentran los detalles personales del profesional o asesor.

- **News:** Sección donde el asesor puede acceder a noticias relacionadas con los cursos.

- **Reviews:** Sección donde se muestran las opiniones recibidas de los estudiantes a los que el asesor ha atendido.

- **Configuration:** Sección donde el asesor puede realizar ajustes en la configuración estándar de la plataforma.

### 4.2.3 SEO Tags and Meta Tags
A continuación, se presentarán los SEO Tags y Meta Tags empleados en la Landing Page con el objetivo de mejorar su visibilidad en los motores de búsqueda.

## Landing Page:
<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149750076038713425/image.png" alt="SEO-tags-and-Meta-Tags" >

### 4.2.4 Searching Systems
En las próximas secciones, se presentarán los sistemas de búsqueda incorporados para facilitar a nuestros usuarios la localización de la información que necesitan.
Para la Landing Page, no se ha integrado un sistema de búsqueda, dado que la información se encuentra segmentada y enlazada en el menú principal. En consecuencia, los visitantes podrán acceder a toda la información esencial de nuestra solución, como nuestra dedicación, servicios y, sobre todo, podrán encontrar los detalles de contacto para comunicarse con nosotros.
Para el caso del Web Application:

#### Segmento 1: Estudiantes que buscan ayuda en los cursos de Arquitectura
- **Seguimiento del Proceso de la Maqueta:**
Esta sección permitirá a los estudiantes revisar su desempeño y avance en cada materia que están estudiando. Si un estudiante desea revisar resultados específicos de algún curso, puede aplicar filtros basados en fechas y estado del desempeño (Aprobado/Reprobado). Una vez aplicados los filtros, o incluso si no se aplican, los resultados se mostrarán en un formato de lista con información resumida. Al hacer clic en un curso específico, se mostrarán resultados detallados.
 
- **Mentores Disponibles:** Los estudiantes podrán aplicar filtros basados en diferentes criterios como materia, preferencia de idioma, experiencia, etc. La información filtrada se mostrará en formato de lista, mostrando detalles clave sobre cada mentor, como su nombre, especialización y calificación con estrellas (5 estrellas indican un servicio de alta calificación).
#### Segmento 2: Profesores y Asesores
- **Lista de Estudiantes:** Los mentores tendrán la capacidad de buscar estudiantes específicos utilizando una barra de búsqueda. También podrán utilizar filtros como género y fecha de interacción para reducir la lista. La información filtrada se mostrará en formato de lista, mostrando detalles básicos de cada estudiante, como su nombre y curso.
- **Resumen de Ganancias:** Los mentores académicos pueden filtrar transacciones según su estado (Completadas, Pendientes, Canceladas) para administrar eficazmente sus ganancias.
- **Horario de Citas:** Los mentores tendrán un calendario donde podrán ver y gestionar sus citas con los estudiantes en días específicos. Al hacer clic en una fecha, podrán ver una lista de citas ordenadas cronológicamente (primeras citas próximas). Si los mentores necesitan acceder a información específica de un estudiante, pueden usar la función de búsqueda por nombre, que incluye autocompletado para evitar errores.

#### Ambos segmentos

- **Sección de noticias:** Es esta sección, tanto los grupos objetivo podrán explorar las noticias relevantes mediante una barra de búsqueda, en la cual deberán introducir el título de la noticia o términos clave. Las noticias serán seleccionadas en función de las palabras clave proporcionadas o si el título exacto de la noticia de los cursos es ingresado correctamente.

### 4.2.5 Navigation Systems
A continuación, se expondrán los sistemas de navegación diseñados para permitir que nuestros usuarios naveguen a través de las diferentes partes de contenido e información.

Como se mencionó previamente en los sistemas de etiquetado, tenemos cuatro "encabezados" en la Landing Page: Home, About, Services y Contact. Estas secciones están dispuestas como un menú horizontal global en la parte superior de la Landing Page. Esta división en cuatro secciones tiene la intención de evitar que los clientes tengan que desplazarse verticalmente a través de una cantidad considerable de información. Esta disposición facilita la navegación por nuestro contenido. La estrategia es que los usuarios primero revisen la sección Home, donde encontrarán la información más relevante que captará su atención, y luego exploren el resto del menú de izquierda a derecha.

Por otro lado, en el caso del Web Application, contamos con una barra de navegación global lateral-vertical donde se encuentran las principales secciones de la interfaz del usuario. Estas secciones se navegan de la siguiente manera:

- **Home**: Esta sección es la que aparece automáticamente al iniciar sesión y muestra noticias relevantes y opciones específicas para cada grupo objetivo. Los estudiantes tienen opciones como buscar asesores, ver su perfil, explorar noticias relacionadas con los cursos y configurar preferencias.
- **My profile:** Si el usuario desea editar su perfil, solo necesita acceder a esta sección ubicada en la barra de navegación lateral-vertical global.
- **News:** Si el usuario desea ver noticias relacionadas con los cursos, puede ingresar a esta sección que se encuentra en la barra de navegación lateral-vertical global y seleccionar la noticia de su interés.
- **Configuration:** Si el usuario desea ajustar la configuración de la interfaz, puede ingresar a esta sección que se encuentra en la barra de navegación lateral-vertical global y realizar los cambios pertinentes.
- **Learning Resources:** Si el estudiante desea revisar sus recursos de aprendizaje, puede acceder a esta sección ubicada en la barra de navegación lateral-vertical global y seleccionar el recurso que estaba buscando.
- **Reviews:** Si el estudiante desea revisar las reseñas de los asesores, solo debe ingresar a esta sección ubicada en la barra de navegación lateral-vertical global.

## 4.3 Landing Page UI Design

Las Landing Pages son herramientas utilizadas con el propósito de convertir a los visitantes en potenciales clientes, empleando estrategias como mensajes impactantes y presentación de información sobre el producto, entre otros enfoques. Por esta razón, se tomó la decisión de aprovechar esta herramienta y crear versiones preliminares tanto para dispositivos móviles como para computadoras.

En la versión móvil, se mantiene el mismo contenido que en la versión para computadoras, pero con un diseño reorganizado para ajustarse al tamaño de los dispositivos móviles. También se incluye un botón que facilita la navegación cómoda a través de la Landing Page en estos dispositivos. Este diseño práctico mejora la usabilidad de las opciones y ofrece una presentación visual amigable para los usuarios.

Por otro lado, en la versión para computadoras, se diseñaron ventanas con opciones específicas que buscan facilitar la comprensión por parte del usuario. Cada opción del sitio web está acompañada de una descripción detallada para evitar confusiones. Además, la barra de navegación se mantiene en una posición fija, lo que garantiza que esté siempre disponible para el usuario y le permite explorar la Landing Page de manera cómoda en todo momento.


## 4.3.1 Landing Page Wireframe

En esta sección, se presentará la estructura fundamental para el diseño del sitio web de nuestra aplicación. Se establecerán bases que brindarán una comprensión más clara del contenido que será exhibido en la plataforma, tanto en la versión para computadoras como en la versión móvil.

La Landing Page debe ser dimensionada de manera adecuada para adaptarse a las distintas pantallas de los dispositivos, asegurando que la información se encuentre centrada en la pantalla para una visualización cómoda por parte del usuario.
Nuestro enfoque es proporcionar información precisa sin generar abrumamiento al usuario. Para lograr esto, ofrecemos una barra de navegación estática que simplifica la exploración a través de la Landing Page, brindando al usuario una experiencia de navegación fluida y accesible.


**Desktop Web**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523301002117232/image.png" alt="wireframe-desktop-web-header" >

Diseño del menú de la plataforma web: Se expone la estructura fundamental que contendrá las opciones de mayor relevancia para la comodidad y satisfacción del usuario.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523358027874314/image.png" alt="wireframe-desktop-web-know-us" >

Opción que muestra datos para conocer mejor la plataforma. Servicios para ambos segmentos:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523400910458890/image.png" alt="wireframe-desktop-web-student-services-and-services-for-teachers" >

Sección de contacto y novedades, donde se proporciona información sobre cómo comunicarse y las últimas actualizaciones de la plataforma.

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149753353262338108/image.png" alt="us" >

Link:  https://www.figma.com/file/ZBPfZwKvSmHGXChepVoi0n/WireFrame-Landing-Page-(StudyMentor)?type=design&node-id=0%3A1&mode=design&t=17uUXsFuZe7hYKGL-1

**Mobile Web** 

Se visualiza la estructura del menú de inicio diseñado para la comodidad del usuario, presentando el icono que despliega las alternativas de navegación.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523488118415370/image.png" alt="wireframe-mobile-web-header" >

Se muestra un conjunto de opciones en un bloque que forma parte de la lista de herramientas del servidor, presentando información específica de la aplicación en ciertas situaciones.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149524974185500672/image.png" alt="wireframe-mobile-web-know-us-part-1" width="" height="548">
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525001050005524/image.png" alt="wireframe-mobile-web-know-us-part-2" >

Se exhiben los servicios disponibles para ambas audiencias objetivo.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525616534753300/image.png" alt="services-for-teachers" width="" height="548">
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525603121369228/image.png" alt="student-services" height="548" >

Se presenta el último bloque de la aplicación, describiendo el contenido relacionado con la comunicación entre el servicio y el usuario.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525636629671996/image.png" alt="us" height="548" >
<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149753549157314610/image.png" alt="contact-us" width="370" height="420" >

Link:  https://www.figma.com/file/ZBPfZwKvSmHGXChepVoi0n/WireFrame-Landing-Page-(StudyMentor)?type=design&node-id=0%3A1&mode=design&t=17uUXsFuZe7hYKGL-1

### 4.3.2 Landing Page Mock-up
Se muestra una vista inicial que representa la estructura fundamental de nuestro sitio web, describiendo su contenido en detalle, aplicando los colores correspondientes de acuerdo con nuestras directrices de estilo e incorporando imágenes pertinentes para mejorar la comprensión de las ideas que deseamos comunicar al usuario de manera más efectiva.

**Desktop Web Browser**

Se presenta la variante del menú de la plataforma, describiendo de manera minuciosa los contenidos fundamentales y las opciones que brindan al usuario un mayor entendimiento de nuestro sistema.

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149750933828419594/image.png" alt="desktop-web-browser-header">

Cuando se selecciona la alternativa "Know Us" en la barra de herramientas del menú principal, se despliegan tres alternativas para que el usuario pueda optar por aquella que mejor se ajuste a sus necesidades y así obtener información detallada sobre nuestro proyecto.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527810629718117/image.png" alt="desktop-web-browser-know us">

Se presenta los servicios que posee el usuario a lo largo del consumo del software.

**Usuario: Estudiantes**


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527834344296568/image.png" alt="desktop-web-browser-student-services">

**Usuario: Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751071342870698/image.png" alt="desktop-web-browser-services-for-teachers">

En el último segmento de la plataforma, se exhibe una breve descripción de contacto, junto con la alternativa de comunicarse con nosotros para compartir sus preguntas y requerimientos.

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751213684969492/image.png" alt="desktop-web-browser-us">

Link: https://www.figma.com/file/rbo4oMtSGbvfsV14pq8Xde/Mockup-Landing-Page-(StudyMentor)?type=design&node-id=0%3A1&mode=design&t=12wH2Nbv9DxmtQ2v-1

**Mobile Web Browser**

Se muestra la sección de menú principal en la versión móvil de la Landing Page, con las opciones más relevantes para nuestra audiencia objetivo y un resumen conciso de nuestro software.

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751334057287780/image.png" alt="mobile-web-browser-header">

Se presenta la sección de "Know Us", que proporciona detalles sobre el proceso de nuestros servicios según el profesional de salud designado, responde consultas sobre el funcionamiento del sistema, comparte información sobre nuestra misión y brinda detalles de nuestras consultas.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528858266189825/image.png" alt="mobile-web-browser-know-us">

Se presenta el conjunto de servicios disponibles para los estudiantes y los profesionales interesados en nuestra aplicación de software.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528881544568862/image.png" alt="mobile-web-browser-service">

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528904785199144/image.png" alt="mobile-web-browser-student-services">

<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751509081391254/image.png" alt="mobile-web-browser-services-for-teachers" width="350">

Se muestra como último bloque de la plataforma, un resumen breve de información de contacto, así como la posibilidad de comunicarse con nosotros y compartir cualquier pregunta o necesidad que puedan tener.


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149530985420042300/image.png" alt="mobile-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751691672039557/image.png" alt="mobile-web-browser-contact-us" height="540">

Link: https://www.figma.com/file/rbo4oMtSGbvfsV14pq8Xde/Mockup-Landing-Page-(StudyMentor)?type=design&node-id=0%3A1&mode=design&t=12wH2Nbv9DxmtQ2v-1

## 4.4 Web Applications UX/UI Design
## 4.4.1 Web Applications Wireframes

<h3 font-style=bold>Segmento Objetivo Estudiante</h3>
<img src="https://media.discordapp.net/attachments/783068752958717972/1149839871914037318/image.png" width="" height="" />

Link: https://www.figma.com/file/xPAYcj8uHxGyNjtZntlNNK/Wireframes-Studymentor?type=design&node-id=19-116&mode=design&t=BIq6W3P0wE3qJZz2-0

<h3 font-style=bold>Segmento Objetivo Tutor</h3>
<img src="https://media.discordapp.net/attachments/783068752958717972/1149840626154741932/image.png?width=938&height=559" width="" height="" />

## 4.4.2 Web Applications Wireflows Diagrams

<h3 font-style=bold>Segmento Objetivo Estudiante</h3>

User Goal: Como estudiante, deseo iniciar sesión para ingresar a la aplicación.<br>
Descripción:
En este wireflow, se evidencia el flujo que el estudiante seguirá para poder iniciar sesión. Primero clickeará la opción de “Student” e ingresará su email, contraseña y tendrá que pasar por un captcha. De no tener una cuenta, clickea en sign up y tendrá que ingresar su información personal para registrarse.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842093339054130/image.png" width="" height="" />

User Goal: Como estudiante, deseo registrarme para ingresar a la aplicación.<br>
Descripción:
En este wireflow, se evidencia el flujo que el estudiante seguirá para poder iniciar sesión. Primero clickeará la opción de “Student” y luego seleccionará la opción de Sign Up, finalmente ingresará sus datos necesarios para poder registrarse exitosamente.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842290760745051/image.png" width="" height="" />


User Goal: Como estudiante, deseo poder cambiar mis datos.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Despues de ingresar a la aplicación, estará en la pantalla de inicio, al darle a la opción “Profile”, irá a la sección la cual puede ver sus datos personales, ahí mismo tendrá una opción para editar sus datos. Finalmente, en la vista de editar, podrá actualizar los datos personales que el estudiante desee, se guardará cuando le de click al botón “Save”.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842653748408330/image.png">

User Goal: Como estudiante, deseo ver a todos los tutores libres.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Después de ingresar a la aplicación, estará en la pantalla de inicio, al darle a la opción “Tutors”, irá a la sección la cual todos los tutores libres y sus especialidades, ahí mismo tendrá una opción para visualizar más sobre ese tutor. Al clickar este botón, podrá visualizar información detallada del tutor, así como sus estudios, pudiendo descargar estos documentos.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842654092329030/image.png?width=1200&height=308">

User Goal: Como estudiante, deseo contratar a un tutor.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de seleccionar al tutor que desee, verá su información completa y un botón para realizar una clase, al clickar ese botón, podrá visualizar los horarios en los que está disponible el profesor y el costo de las clases. Finalmente, habiendo ya escogido el horario preferido, podrá pagarle al profesor ingresando los datos de su tarjeta y confirmando la transacción .

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842681732800602/image.png?width=1200&height=311">

User Goal: Como estudiante, deseo visualizar los días que tengo clase.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación, en la pantalla de inicio, podrá visualizar el botón “Schedule”, el cual permite la visualización de un horario en el que verá que días tiene clases, para no perderse ninguna.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842745930817607/image.png?width=1200&height=426">

User Goal: Como estudiante, deseo visualizar las calificaciones con el tutor contratado.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación, en la pantalla de inicio, podrá visualizar el botón “Califications”, el cual permite la visualización de las calificaciones, lo cual le sirve para verificar su avance. Asimismo, las evaluaciones que aún no han sido calificadas le saldrán como “No Calificada”.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842746182467695/image.png?width=1200&height=453">

User Goal: Como estudiante, deseo visualizar las reseñas de otros estudiantes a cierto tutor.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación y seleccionar a un tutor en la lista de tutores, tendremos un botón de “See review”, el cual nos permitirá visualizar las reseñas de otros estudiantes sobre ese tutor. Asimismo, podremos publicar una reseña sobre el tutor al cual hemos contratado.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842745930817607/image.png?width=1200&height=426">

## 4.4.3 Web Applications Mockups

<h3 font-style=bold>Segmento Objetivo Estudiante</h3>

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842808652451961/image.png?width=1200&height=511">

Link: https://www.figma.com/file/xYHRwXtAQhBYRZGyrciRHk/Mockups-Web-Application?type=design&node-id=0-1&mode=design&t=oZQZa5UKYVU4nEeg-0


<h3 font-style=bold>Segmento Objetivo Tutor</h3>

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842840743059516/image.png?width=1015&height=559">

Link: https://www.figma.com/file/xYHRwXtAQhBYRZGyrciRHk/Mockups-Web-Application?type=design&node-id=1-901&mode=design&t=oZQZa5UKYVU4nEeg-0

## 4.4.4 Web Applications User Flow Diagrams

Segmento Objetivo Estudiantes
User Goal: Como estudiante, deseo iniciar sesión para ingresar a la aplicación.<br>
Descripción:
En este wireflow, se evidencia el flujo que el estudiante seguirá para poder iniciar sesión. Primero clickeará la opción de “Student” e ingresará su email, contraseña y tendrá que pasar por un captcha. De no tener una cuenta, clickea en sign up y tendrá que ingresar su información personal para registrarse.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842875874562218/image.png?width=1200&height=522">

User Goal: Como estudiante, deseo registrarme para ingresar a la aplicación.<br>
Descripción: En este wireflow, se evidencia el flujo que el estudiante seguirá para poder iniciar sesión. Primero clickeará la opción de “Student” y luego seleccionará la opción de Sign Up, finalmente ingresará sus datos necesarios para poder registrarse exitosamente.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149842900990042202/image.png?width=1200&height=326">

User Goal: Como estudiante, deseo poder cambiar mis datos.<br>
Descripción: En este wireflow se evidencia el flujo que el estudiante seguirá. Despues de ingresar a la aplicación, estará en la pantalla de inicio, al darle a la opcion “Profile”, irá a la sección la cual puede ver sus datos personales, ahí mismo tendrá una opción para editar sus datos. Finalmente, en la vista de editar, podrá actualizar los datos personales que el estudiante desee, se guardará cuando le de click al botón “Save”.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149843132163313756/image.png?width=1200&height=299">

User Goal: Como estudiante, deseo ver a todos los tutores libres.<br>
Descripción:
En este wireflow se evidencia el flujo que el estudiante seguirá. Después de ingresar a la aplicación, estará en la pantalla de inicio, al darle a la opción “Tutors”, irá a la sección la cual todos los tutores libres y sus especialidades, ahí mismo tendrá una opción para visualizar más sobre ese tutor. Al clickar este botón, podrá visualizar información detallada del tutor, así como sus estudios, pudiendo descargar estos documentos.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844039072501790/image.png?width=1200&height=331">

User Goal: Como estudiante, deseo contratar a un tutor.<br>
Descripción: En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de seleccionar al tutor que desee, verá su información completa y un botón para realizar una clase, al clickar ese botón, podrá visualizar los horarios en los que está disponible el profesor y el costo de las clases. Finalmente, habiendo ya escogido el horario preferido, podrá pagarle al profesor ingresando los datos de su tarjeta y confirmando la transacción .

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844121452806274/image.png?width=1200&height=299">

User Goal: Como estudiante, deseo visualizar los días que tengo clase.<br>
Descripción: En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación, en la pantalla de inicio, podrá visualizar el botón “Schedule”, el cual permite la visualización de un horario en el que verá que días tiene clases, para no perderse ninguna.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844121759006740/image.png?width=1200&height=481">

User Goal: Como estudiante, deseo visualizar las calificaciones con el tutor contratado.<br>
Descripción: En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación, en la pantalla de inicio, podrá visualizar el botón “Califications”, el cual permite la visualización de las calificaciones, lo cual le sirve para verificar su avance. Asimismo, las evaluaciones que aún no han sido calificadas le saldrán como “No Calificada”.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844122027438090/image.png?width=1200&height=423">

User Goal: Como estudiante, deseo visualizar las reseñas de otros estudiantes a cierto tutor.<br>
Descripción: En este wireflow se evidencia el flujo que el estudiante seguirá. Luego de ingresar a la aplicación y seleccionar a un tutor en la lista de tutores, tendremos un botón de “See review”, el cual nos permitirá visualizar las reseñas de otros estudiantes sobre ese tutor. Asimismo, podremos publicar una reseña sobre el tutor al cual hemos contratado.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844197319393280/image.png?width=1200&height=443">

## 4.4.5 Web Applications Prototyping

A continuación, se detallarán los principales criterios para las decisiones de interacción (elementos de la interfaz y los principios aplicados a ellos) relacionados con la Arquitectura de información para nuestra aplicación web. Asimismo, se adjuntará un video evidenciando lo propuesto para una mejor comprensión.

**Botones/Tarjetas del menú principal**

Cada segmento objetivo tiene su propio menú principal con sus propios botones. Asimismo, incluimos unas tarjetas con las principales noticias. Para ello nos hemos basado en los siguientes principios: 

•	Principio de los objetos: Agrupamos el contenido relacionado dentro de sus botones y tarjetas respectivas, los cuales se comportarán de una forma determinada. Asimismo, cada botón tendrá sus propios atributos respecto a cómo visualizar la información contenida en ellos.

**Listas**

Distintas secciones dentro de nuestra aplicación utilizan las listas, tales como: lista de estudiantes, lista de tutores, valoraciones, etc. Para ello nos hemos basado en los siguientes principios: 
•	Principio de las elecciones: Darle al usuario final demasiadas opciones puede ser abrumador, así que nuestras listas tienen un límite de muestra, es decir, si tenemos muchos elementos en nuestra lista, entonces solo mostraremos diez de ellos, el usuario podrá decidir si le es necesario ver el resto a través de un botón (ver más). 

•	Principio del crecimiento: Al utilizar las listas, no nos vemos afectados por el crecimiento, ya que, cualquier información nueva adicionada se colocará al final de la lista.

**Resúmenes de contenido** 

Estos resúmenes están estrechamente relacionados con las listas de estudiantes o tutores, ya que, ambos necesitan información de la otra parte, ya sea para separar una clase o visualizar los estudiantes. Es por ello, por lo que se sigue el siguiente principio: 

    •   Principio de divulgación: Solo mostramos la información suficiente para ayudar a nuestros usuarios a comprender con qué tipo de tutor o estudiante van a tratar. Si deciden profundizar más a detalle, lo seleccionarán y serán redirigidos a su perfil. 

**Menús** 

Nuestra aplicación consta de 2 menús, uno se encuentra en la parte inferior de forma horizontal (secciones principales) y el otro en la parte lateral derecha de forma vertical (secciones secundarias). Esto debido al siguiente principio: 

•   Principio de navegación enfocada: Debemos tener en cuenta cómo nuestros usuarios navegan por el contenido de nuestra aplicación, por lo que se implementaron estos dos menús. El objetivo fue tener dos diferentes menús para los dos tipos de información. Introducción de los flujos de interacción mostrados en el video: 

•   Principales:

    o   Chat: El estudiante o el tutor, se comunica por medio de un chat con su tutor o su estudiante respectivamente, en el cual pueden establecer la plataforma en la cual tendrán la clase, etc. 

    o   Verificar tu horario: Tanto el estudiante como el tutor pueden visualizar los días que tiene clase. En el caso del tutor, visualiza todas sus clases y las horas. Por el lado del estudiante puede visualizar la clase con el profesor al cual está inscrito. 

    o   Verificar tus calificaciones: El estudiante puede visualizar las notas de su curso de tutoría.

    o   Verificar tus valoraciones: El tutor puede visualizar las valoraciones que los estudiantes le ponen junto con las estrellas y un comentario.

•   Secundarios: 

    o   Ver perfil de usuario: El usuario navega hacia su perfil a través del menú principal de la parte lateral. 

    o   Ver lista de tutores: El estudiante revisa la lista de tutores para luego poder ver información más detallada sobre él.

    o   Ver lista de estudiantes: El tutor revisa la lista de sus estudiantes  para luego poder ver información más detallada sobre él .


**Segmento Estudiante**

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844234426404885/image.png">

**Segmento Tutor**

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844268588990625/image.png?width=969&height=559">

Prueba del prototipo

<img src="https://media.discordapp.net/attachments/783068752958717972/1149844351669784706/image.png">

Link del video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912404_upc_edu_pe/EZaLPK6wlUpOgfLV-oBVAyUBULxzF1O9hDPXO1VkDAF43g?e=zY8noL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19

## 4.6 Domain -Driven Software Architecture
Los diagramas de arquitectura de software nos ayudan a plantear el sistema de nuestro software, basándonos en el enfoque de desarrollo de Domain Driven Design.
## 4.6.1 Software Architecture Context Diagram.
A continuación presentamos el diagrama de contexto de nuestra arquitectura, el cual muestra como encaja en el mundo con los usuarios que lo usa y con los sistemas de software externo que interactúa.
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875602850058261/structurizr-85920-SystemContext-001.png?width=1037&height=676">
## 4.6.2 Software Architecture Container Diagrams.
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875604380979300/structurizr-85920-Container-001.png?width=993&height=676">
En esta sección indicamos los contenedores de nuestro diagrama de contexto. Donde se muestan los elementos tecnológicos de alto nivel.
## 4.6.3 Software Architecture Components Diagrams.
En este apartado se presenta el diagrama de componentes, donde se detallan los componentes que pertencen a cada uno de nuestros contenedores relacionados a los bounded context de nuestro proyecto.

Asesoría Component Diagram :
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875603089129562/structurizr-85920-Component-001.png?width=652&height=676">
Monitoreo Component Diagram :
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875603466620938/structurizr-85920-Component-002.png?width=741&height=676">
Seguridad Component Diagram :
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875603827327057/structurizr-85920-Component-003.png?width=964&height=676">
Calficación Component Diagram :
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149875604104167505/structurizr-85920-Component-004.png?width=1127&height=676">

## 4.7 Software Object-Oriented Design.

### 4.7.1. Class Diagrams.
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149876455581417602/Class_Diagram_StudyMentor_2.png?width=1061&height=676">

[<center>LucidChart</center>](https://lucid.app/lucidchart/7e91ac6c-c547-4c10-b791-3165dcb90830/edit?viewport_loc=73%2C-255%2C2978%2C1461%2C0_0&invitationId=inv_3efd66ee-8857-42da-a3e7-09b2bfed885e)

### 4.7.2. Class Dictionary.

En este apartado se presenta la definición de los términos usados en el diagrama de clases para el desarrollo de nuestro proyecto.
+ User: Esta clase representa a los usuarios de nuestra aplicación sin importar el rol que desempeñan dentro del app. Es padre de las clases que representan nuestros segmentos objetivos.
+ Student: Esta clase representa al segmento objetivo de estudiantes que buscan una asesoría en línea respecto a un curso. Se encuentran los métodos relacionados a las necesidades del estudiante como añadir una asesoría y cambiar sus datos sobre su educación.
+ Asesor: Esta clase representa al segmento objetivo de asesores que buscan generar ingresos a través de su conocimiento, en sus atributos se encuentran objetos de otras clases que sirven para las necesidades del asesor como el manejo de cursos y un horario.
+ TimeBlock: Esta clase representa los bloques de tiempo disponibles por el asesor, el cual se encuentra en modo de un arreglo dentro de la clase Asesor, esta clase indica las fechas y horas en las que el asesor tiene bloques de tiempo disponibles para los estudiantes que requieran de su servicio.
+ Course: Esta clase representa el curso impartido por los asesores, para que los estudiantes puedan seleccionar la especialidad y temas de las asesorías que necesitan.
+ Advisory: Esta clase representa las asesorías ya registradas por parte de los estudiantes en un bloque de tiempo libre del asesor. Se encuentran métodos para modificar los datos de la asesoría como la fecha, el tiempo que se va a impartir y finalmente un método para cancelar la asesoría.
+ Review: Esta clase representa la reseña de la asesoría por parte del estudiante, incluye atributos para que el estudiante deje un comentario y un puntaje. Tiene métodos por si el estudiante desea modificar la calificación a la asesoría brindada.



## 4.8 Database Design
### 4.8.1 Database Diagram
<img src="https://cdn.discordapp.com/attachments/1149190528756363340/1149751856625627146/image.png" alt="database-diagram">



## Entidades de la base de datos:

### Tabla: Appointment (Cita)

Almacena información sobre las citas programadas entre estudiantes y mentores.

**Atributos:**

- **Id: Identificador único de la cita.**

- **StudentId: Identificador del estudiante que solicita la cita.**

- **MentorId: Identificador del mentor o asesor de arquitectura asignado a la cita.**

- **Date: Fecha de la cita.**

- **Time: Hora de la cita.**

- **Description: Descripción detallada de la cita.**

- **MaterialId: Identificador del material asociado a la cita (si aplica).**

- **PaymentId: Identificador del detalle de pago asociado a la cita.**


### Tabla: Mentor (Mentor o Asesor)

Contiene información sobre los mentores registrados en la plataforma.

**Atributos:**

- **Id: Identificador único del mentor o asesor.**

- **FirstName: Nombre del mentor.**

- **LastName: Apellido del mentor.**

- **Specialty: Especialidad o área de expertise del mentor.**

### Tabla: Payment (Pago)

Almacena detalles de los pagos realizados por los estudiantes.

**Atributos:**

- **Id: Identificador único del registro de pago.**

- **PaymentDetailId: Identificador del detalle de pago.**

- **AppointmentId: Identificador de la cita asociada al pago.**

### Tabla: PaymentDetail (Detalle de Pago)

Guarda información detallada sobre los pagos, como subtotal, descuento y retención.

**Atributos:**

- **Id: Identificador único del detalle de pago.**

- **Subtotal: Monto subtotal del pago.**

- **Discount: Descuento aplicado al pago.**

- **RetentionPercentage: Porcentaje de retención en el pago.**

- **RetentionAmount: Monto retenido.**


### Tabla: Record (Registro de Proyecto)

Registra eventos o actividades, como proyectos, en la plataforma.

**Atributos:**

- **Id: Identificador único del registro de proyecto.**

- **Date: Fecha del registro.**

- **Time: Hora del registro.**

- **Description: Descripción detallada del proyecto o trabajo.**

- **StudentId: Identificador del estudiante relacionado con el registro.**

### Tabla: Score (Puntaje)

Contiene las puntuaciones y comentarios proporcionados por los estudiantes sobre las citas.

**Atributos:**

- **Id: Identificador único del puntaje.**

- **Score: Puntuación otorgada.**

- **Comment: Comentario relacionado con el puntaje.**

- **Date: Fecha del puntaje.**

- **AppointmentId: Identificador de la cita asociada al puntaje.**

### Tabla: Service (Servicio)

Almacena información sobre los servicios ofrecidos en la plataforma, como tutorías o clases particulares.

**Atributos:**
- **Id: Identificador único del servicio.**

- **Name: Nombre o título del servicio.**

- **Description: Descripción del servicio.**

- **Price: Precio del servicio.**

### ServiceByAppointment (Servicio por Cita)

ServiceByAppointment (Servicio por Cita)

**Atributos:**
- **AppointmentId: Identificador de la cita.**

- **ServiceId: Identificador del servicio.**


### Tabla: Student(Estudiante)

Contiene información sobre los estudiantes registrados en la plataforma.

**Atributos:**
- **Id: Identificador único del estudiante**

- **FirstName: Nombre del estudiante.**

- **LastName: Apellido del estudiante.**

- **Age: Edad del estudiante.**
## 5.1 Software Configuration Management.
En este apartado se presentan las convenciones decididas en grupo, las cuales nos permiten mantener consistencia y legibilidad en el desarrollo de la solución.
## 5.1.1 Software Development Environment Configuration.
En esta primera parte damos a conocer las aplicaciones y software utilizados en el desarrollo del proyecto. A continuación se enlista dichos elementos en sus respectivas clasificaciones:
+ Project Management: Esta doctrina basada en la organización de las tareas del proyecto tiene como objetivo mejorar el éxito de uno o más proyectos. Para la asignación de responsabilidades se usaron herramientas de chat, sin embargo estas asignaciones quedan reflejadas en el siguiente software:
  <br>a) Trello: Esta herramienta permite a nuestro equipo gestionar nuestro proyecto y flujo de trabajo, así mismo nos permite asignarnos tareas y personalizar según nuestras necesidades.
  <br><br>
+ Requirements Management: Este proceso nos ayudó a identificar las necesidades y requisitos de nuestros usuarios, poniéndonos en el lugar de la persona que necesita una solución a la problemática que tratamos de resolver. Para esto se usó:
  <br>a)Pivotal Tracker: Este software de gestión de proyectos es de gran ayuda por su manejo de user stories, agrupación de estas en epics y su calificación de dificultad o tiempo por puntaje. Otra de las razones del uso de este programa es la vista en tiempo real del proyecto.
  <br><br>
+ Product UX/UI Design: El diseño UX se centra en satisfacer las necesidades de los usuario en la experiencia que tienen con nuestro software. Por otro lado, el diseño UI busca diseñar la interfaz que usarán los usuarios, en este caso la aplicación web que desarrollamos. Para este apartado se usaron las siguientes herramientas:
  <br>a) Uxpressia: Para el uso de esta herramienta, primero se recopiló información de los usuarios y sus necesidades. Con este software se desarrollaron los User Persona, Empathy Map, Journey Map y Impact Map.
  <br>b) MIRO: El principal uso de esta herramienta fue para la lluvia de ideas gracias a la flexibilidad de su pizarra colaborativa. Aquí se formularon ideas primerizas sobre los problemas y necesidades de los clientes, así mismo para la identificación de los Bounded Context de nuestro proyecto.
  <br>c) Figma: Este editor de gráficos y herramienta de generador de prototipos nos ayudó a desarrollar los artefactos correspondientes al diseño UI, considerando desde la creación de wireframes y mockups hasta la presentación del prototipo.
  <br>d) LucidChart: Con esta herramienta desarrollamos los diseños UML, la principal razón del uso de esta herramienta fue el poder colaborar en tiempo real la creación del diagrama.
  <br><br>
+ Software Development: Este concepto abarca el conjunto de actividades dedicadas al proceso de creación, diseño y despliegue del software. Para el cumplimiento de estas actividades usamos lo siguiente:
  <br>a) Github: En esta plataforma alojamos el código que desarrollamos en conjunto para su posterior despliegue.
  <br>b) Webstorm: Este IDE nos ofrece un entorno de desarrollo integrado para JavaScript y otras tecnologías relacionadas como HTML y CSS
  <br>c) Rider: Este IDE nos ofrece herramientas para el desarrollo web y su compatibilidad con bases de datos, lo cual abarca gran parte de las necesidades para desarrollar aplicaciones ASP.NET Core.
  <br><br>
+ Software Testing: Para este primer hito todos los integrantes realizaron pruebas del landing page antes de realizar una modificación en sus propias máquinas en sus respectivas IDE de uso preferido personal.
  <br><br>
+ Software Documentation: Para la documentación de software hemos utilizado dos herramientas, Github y Google Drive:
  <br>a) Github: En esta herramienta colaborativa hemos añadido toda la documentación relacionada en esta entrega en el formato MarkDown.
  <br>b) Google Drive: Hemos usado Google Docs para las tareas que requieren desarrollar un artefacto entre dos o más personas en tiempo real para posteriormente pasarlo a nuestro repositorio en formato MarkDown.


## 5.1.2 Source Code Management.
El medio y esquema de organización que se aplicó para el seguimiento de las modificaciones en el desarrollo de nuestro proyecto se realizó en Github con repositores respectivos para cada elemento de la arquitectura de desarrollo. Para esta primera entrega compartimos el repositorio de nuestra Landing Page.
<br>

URL Repositorio Landing Page:
https://github.com/Aplicaciones-Web-SW53-Grupo-1/Landing-Page

Para los commits de nuestro repositorio se tomó en cuenta el modelo concebido en 2010, Git Flow:

La manera que se plantea usar git flow es seguir su concepto de crear ramas a parte de la principal (main branch). Las ramas que se planea crear:
+ Main Branches

+ Support Branches

+ Feature Branches


Cada feature debe tener su propia rama y deben tener una convención que se usarán en todas las branches. La convención a usar:

Feature/name:

Por ejemplo :
+ feature/registro
+ feature/studentClass
+ feature/advisoryTransaction

Para el nombre de commit se usará “Conventional Commits”, este indica la estructura que deben tener los commit de  nuestras ramas.

+ tipo(Alcance opcional): descripción del commit

Para especificar el tipo se encuentran la siguientes definiciones:
+ feat: cuando se añade un feature
+ fix: cuando se soluciona un error.
+ build: cuando se modifican las herramientas de compilación
+ chore: modificaciones privadas
+ refactor: cuando solo se modifica la documentación
+ perf: cuando se mejora el rendimiento
+ style: commits relacionados al estilo, no afectan la lógica
+ test: commits para la creación de pruebas

El alcance da información que da contexto al commit, para que los demás desarrolladores entiendan el entorno del commit.

La descripción del commit es una parte fundamental y obligatoria del commit, se debe usar imperativo y el texto debe ser en minúsculas.


## 5.1.3 Source Code Style Guide & Conventions.
En este apartado se especifica las convenciones para nombrar elementos y programar en los lenguajes de esta primera entrega.

HTML:
No omitir las etiquetas html y body, aunque no den error, la falta de body puede causar problemas en navegadores antiguos y la falta de la etiqueta html puede corromper a DOM y XML software.
<!DOCTYPE html>
<img src="https://media.discordapp.net/attachments/1143747947322941440/1149882178235273346/image.png?width=506&height=676">


CSS:
Utilizar nombres de clases que sean posiblemente cortas pero largas si es necesario, para la comprensión de los demás desarrolladores:
+ .nav {}
+ .author {}

Separar los nombres de las clases con guión:
+ .video-id {}
+ .error-status{}

El orden de declaración de los elementos dentro de una clase deben ir en orden alfabético:
+ background: fuchsia;
+ border: 1px solid;
+ -moz-border-radius: 4px;
+ -webkit-border-radius: 4px;
+ border-radius: 4px;
+ color: black;
+ text-align: center;
+ text-indent: 2em;

Aplica sangría en todos los atributos de una clase para representar la jerarquía y mejorar la comprensión:
@media pantalla , proyección {

+ html {
+ fondo : #fff;
+ color : #444; } }

Poner una línea en blanco entre las reglas:
+ html {
+ background: #fff;
+ }

+ body {
+ margin: auto;
+ width: 50%;
+ }

JavaScript:
Usar const and let, la mayoría de veces usar variables const a no ser que necesite ser reasignado su valor, evitar el uso de var.

+ Una variable por declaración:
  No hacer let a = 1, b = 2

+ No usar el constructor Objeto, usar un constructor literal {name: ‘gio, …}

+ Utilizar CamelCase para nombres de variables y funciones:
  const mySchedule = {};
  func transferMoney(a,b) {}

+ Utilizar Pascal para nombres de clases y constructores:
  MiClase{
  MiClase(){}
  }

Utilizar punto y coma al final de una sentencia, aunque javaScript permite omitir el uso de estas se considera buena práctica incluirlo para evitar posibles errores.

## 5.1.4 Software Deployment Configuration.

Para el despliegue de nuestra Landing Page, accedemos al repositorio donde tenemos nuestro proyecto:
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149881395603325050/image.png?width=1149&height=676">
Nos dirigimos a la sección Settings de nuestro repositorio, nos dirigimos en el apartado Pages:
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149881460409511936/image.png?width=1195&height=676">
Definimos la rama desde donde vamos despegar nuestro proyecto y guardamos. Con esto se genera el URL del despliegue de nuestra landing page.
<img src = "https://media.discordapp.net/attachments/1143747947322941440/1149881524825624687/image.png?width=1441&height=640">

## 5.2 Landing Page, Services & Applications Implementation
## 5.2.1. Sprint 1
## 5.2.1.1. Sprint Planning 1

| **Sprint #** | **Sprint 1** |
| --- | --- |
| **Sprint Planning Background** |
| **Date** | 30-08-2023 |
| **Time** | 10:00 PM |
| **Location** | Servidor de Discord del Equipo |
| **Prepared By** | Curi Montero Jonatan Omar |
| **Attendees** | Curi Montero Jonatan Omar/Rafael Arturo Luyo Ramirez/Kurt Matthews Puican Salas/Miguel Angel Ramirez Alfaro/Giovanni Andres Ramos Calderon|
| **Sprint n Review Summary** | En esta entrega no hay un Sprint anterior, por lo tanto, no hay resúmen de Sprint |
| **Sprint n Retrospective Summary** | En esta entrega no hay un Sprint anterior, por lo tanto, no hay resúmen de Sprint |
| **Sprint Goal & User Stories**|
| **Sprint 1 Goal** | La meta de este Sprint es la investigación y desarrollo de nuestro proyecto. Asimismo, consiste en el funcionamiento de la Landing Page, tanto su visualización, el traslado y la visualización de todo lo estipulado. |
| **Sprint 1 Velocity** | 10 Velocity |
| **Sum of Story Points** | 10 Story Points. |


## 5.2.1.2. Sprint Backlog 1

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879572330991646/image.png?width=561&height=559">
<img src="https://media.discordapp.net/attachments/783068752958717972/1149879592434286633/image.png">


## 5.2.1.3. Development Evidence for Sprint Review

En esta sección se presentan los avances de implementación con relación a los productos desarrollados en el presente Sprint. La implementación que se desarrolló fue la primera version del Landing Page, se implementaron las distintas secciones para conocer más sobre nuestra plataforma. Con ello completamos el primer sprint de implementación. 

Integrantes:

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879638244479046/image.png">


<img src="https://media.discordapp.net/attachments/783068752958717972/1149879668774817822/image.png?width=461&height=559">


## 5.2.1.4. Testing Suite Evidence for Sprint Review

No se desarrolló en este sprint, pues en esta parte se presentarán los Unit Tests, Integration Tests y Acceptance Tests automatizados, para Web Services.

## 5.2.1.5. Execution Evidence for Sprint Review

Las vistas implementadas son el navbar con las secciones Home, Knos Us, Services, Contact Us. Esa barra de navegación es fija y mientras el usuario se desplace se mueve junto con la pantalla.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879754636410991/image.png">

Podemos ver la sección de inicio con la información y un botón que para el siguiente sprint direccionará al usuario a la aplicación web.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879797036621874/image.png">

En esta sección pueden conocer más sobre la plataforma y las caracteristicas de esta.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879797338619966/image.png">

Aquí tenemos datos de studymentor.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879816133287966/image.png">

Aqui pasamos a ver los servicios tanto de estudiantes.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879842645483570/image.png">

Como el servicio para tutores como se puede observar aquí. Además, contará con un botón el cual direccionará a la aplicación web.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879866712408094/image.png">

La sección nosotros contiene 2 videos, los cuales por el momento son videos genéricos, pero se reemplazarán con el video about the product y el video about the team.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879886538870935/image.png>

Esta es la última sección, la cual contiene nuestros datos de contacto, y un poco sobre nosotros como empresa.

## 5.2.1.6 Services Documentation Evidence for Sprint Review

No se desarrolló en este sprint, pues en esta sección presentaremos la relación de Endpoints documentados con OpenAPI, relacionados con el alcance del Sprint y con Web Applications.

## 5.2.1.7 Software Deployment Evidence for Sprint Review

Como ya se ha mencionado, la gestión de nuestro código fuente se realizará a través de GitHub. Asimismo, se utilizará Github Pages para la publicación y despliegue de la página. Cada sección del Landing Page que se ha creado deberá aparecer en el siguiente vínculo: https://aplicaciones-web-sw53-grupo-1.github.io/Landing-Page/public/

Para el desarrollo del Landing Page de StudyMentor se han utilizado las siguientes herramientas:

•   Html: Es el lenguaje de marcado que estructuró nuestro Landing Page.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879923033505853/image.png">

•   Css: Es aquel que nos ayudó con el diseño gráfico para que el Landing Page sea agradable e interactuable. 

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879942834827264/image.png">

JavaScript: Nos ayudó a desarrollar la lógica de la integración del navbar, para su uso adecuado en un dispositivo móvil.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149879968663359599/image.png">

El despliegue del Landing Page de StudyMentor se realizó gracias a: 

• Git: Sistema de control de versiones que está pensado en la eficiencia y compatibilidad de versiones. El cual nos ayudó a trabajar en equipo durante el desarrollo del Landing Page.

• GitHub: Plataforma de desarrollo colaborativo. 

• Git Flow: Nos permitió controlar el avance de cada uno de nuestros integrantes con respecto al desarrollo del Landing Page

• Git Hub Pages: Servicio de Github que nos permitió alojar nuestra lading page. 

Los pasos que se realizaron fueron:

-   Como utilizamos Github, nos dirigimos al repositorio donde se encuentra nuestra landing page. Luego a la sección “Settings”.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880000514887760/image.png">

-   Cuando nos encontramos en la configuración, tenemos que darle click a la sección pages.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880025374539796/image.png">

-   Luego, dentro de la sección “pages” tenemos que seleccionar la rama que se va a deployear, en nuestro caso es la rama “main”. Asimismo, tenemos que elegir una carpeta para localizar la publicación, que en nuestro caso será root. Finalmente tendremos el link en la parte superior, agregandole “public” al final del link nos dirigirá a la landing page.

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880047201689703/image.png">

Este es el enlace final:
https://aplicaciones-web-sw53-grupo-1.github.io/Landing-Page/public/ 

## 5.2.1.8 Team Collaboration Insights for Sprint Review

Creamos una organización en Github, donde tendremos todos nuestros repositorios de manera pública.

Link de la organización: https://github.com/Aplicaciones-Web-SW53-Grupo-1 
Link del repositorio con la landing page: https://github.com/Aplicaciones-Web-SW53-Grupo-1/Landing-Page 

Podemos visualizar todos los commits y probamos que todos participamos en la landing page:

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880091267039342/image.png">

Integrantes:

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880070501056542/image.png">

## 5.2.2.7 Team Collaboration Insights for Sprint Review

Para el despliegue de nuestra aplicación web se usó Firebase. Nuestro proyecto se encuentra en el siguiente enlace:
https://studymentor-aplicattionweb-v1.web.app 
Para vincular nuestro proyecto con el servicio en nube que ofrece Firebase se siguió la instalación de dependencias que nos indica la herramienta:
<img src="https://media.discordapp.net/attachments/1143747947322941440/1157082321367879712/image.png?ex=65175062&is=6515fee2&hm=90521d19de7294704bff14b376fa39b84d43401cb513b15cfce58bf839b3fd17&=&width=1277&height=676">

<img src="https://media.discordapp.net/attachments/1143747947322941440/1157082501999763456/image.png?ex=6517508e&is=6515ff0e&hm=2c758d2312f09ddfe7b43a9cac964bec4c4a830d54d6bdddb22bb21e91d1954d&=&width=1061&height=93">
Posteriormente escogemos el directorio dist como la directorio de recursos para nuestro proyecto en Firebase:
<img src="https://media.discordapp.net/attachments/1143747947322941440/1157082583784493176/image.png?ex=651750a1&is=6515ff21&hm=3299fe88415815f1b1e689170cc94e5b0d01303f26395e8916d6a58295c561ba&=&width=1189&height=244">


## 5.2.2.3 Development Evidence for Sprint Review

| Repository                                          | Branch                    | Commit Id                                   | Commit Message                              | Commit message body                       | Committed On   |
|----------------------------------------------------|---------------------------|---------------------------------------------|---------------------------------------------|------------------------------------------|----------------|
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/welcome           | 5d9b45d2781e3d81ff11d2a732f804a4af8f364a | feature(welcome)::add Welcome view and Toolbar added | Se agrego el welcome view y el Toolbar   | 22/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | beff9d223ba8a060ec78113d02468bfe762b7ca4 | build(develop):add Develop branch created | Se creo la rama develop                   | 22/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | 27aedac587a517182f87c109403010b1a57d9cc6 | fx(develop)::add project name fixed        | Se corrigió el nombre del proyecto        | 22/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/registerStudent   | f195e362d221fc419fcce02f82efcc3847047e20 | feature(registerStudent::add Register Student Added | Se agrego register Student                | 24/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/loginStudent      | f195e362d221fc419fcce02f82efcc3847047e20 | feature(loginStudent)::add Login Student Added | Se agregó Login Student                   | 24/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feat/chooseSchedule       | 611cf34ab35be3497282a1508674f7990d989c92 | feat(chooseSchedule9:added schedule component | Se agrego el componente de schedule        | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feat/chooseSchedule       | c2ba10dd825323962928b68abf74408dabbca4da | feat(chooseSchedule9:padding component changed | Se cambió el padding del componente       | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feat/db                   | 99d49e413a83c13f2365a2a3c4f1f4b04268aff1 | feat(db; added schedules data              | Se agregaron datos de Schedule             | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/selected-tutor    | 389ac4cb64ca744751322a4d53e048d4198f0206 | feature(selected-tutor):Add selected tutor component | Se agrego el componente de selected tutor | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/selected-tutor    | 902f6ae73908ae39651cc218b69622ae8d0e233e | feature(selected-tutor):Add selected tutor view | Se agregó la vista del componente selected-tutor | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/selected-tutor    | a1926fa6d93cb9a97dc1924db916f029050ddf5f | feature(selected-tutor): add routes       | Se agrego las rutas de los componentes     | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/chat              | 7f9dc3395c38310e33180d5d148b5385e75ff27f | feature(chat):Add chat component           | Se agrego el componente de chat            | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feat/payment              | 7c66f0b8613a7344f5782064c64cfb093d80ea74 | feat(payment): added payment component and service for fake api | Se agrego el componente de pago y los servicios de la fake api | 25/09/2023 |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/chat              | d4506720c7d89fe7dddc4eb5335eff5a120c5ee8 | feature(chat):Add chat view                | Se agrego la vista del componente de chat  | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/ratings           | 4b0edb05af2d9115a89bbad8fccbf01bbef84b84 | feature(ratings):Add ratings component     | Se agrego el componente de ratings         | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/ratings           | 74255d90a38468928525d6817c5ed6189d689f40 | feature(ratings):Add rating view          | Se agrego la vista del componente ratings  | 25/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feat/calendar             | ce3292e081fe3c9c7c8e0a64e97a4f35079115b7 | feat(calendar): add calendar component    | Se agrego el componente de calendar        | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/score             | 8f30389ca0e9eb86e3cb38cfd6147df7647a8a8c | feat(score): add score component          | Adición del componente de puntaje         | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/tutorlist         | 203451192e591ec2cf4a0fa399e1520d8858a62f | feat(tutor-list): add tutorlist component | Adición del componente de lista de tutores | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/calendarservice   | d737fa9c4886e26716f0ff98143847f8edea5fdb | feat(calendar): add calendar service      | Adición de el servicio de calendario      | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/score-view        | d112f93ea2e4689706ef3ff08a873df5247ff5f8 | feat(score): add score view               | Adición de la vista de puntuación         | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | feature/tutorlist-view    | 0b50de82c47197fef7625bf605343c9537afdb25 | feat(tutor-list): add tutor-list-view and enhancement of router.js, db.json | Adición de la vista de tutor y se realizaron mejoras en 'router.js' y 'db.json' | 26/09/2023 |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | component/studentProfile  | c6a3c31a141b8f932988d9de076956de5999ab9c | feature(edit-home-profile)::add users.vue in components | Adición de users.vue a los componentes de edición de perfil de inicio | 26/09/2023 |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | component/studentProfile  | 0266f0f8b9bf6258e357bc34fcacbe47433a7423 | feature(update)::update components user  | Actualización de componente usuario        | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | component/studentProfile  | 809262cbf007b838c95c645ec29ff5e9815ffcbc | fix(update)::add fixed errors             | Adición de corrección de errores           | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | 00a19beb18b3f8eef375bd3b24ea3362cf53a2a9 | fix(routes): :add fixed routes            | Adición de las rutas corregidas           | 26/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | 22485a8896e02987764c73873d367919f0c3fef5 | fix(routes)::add fixed routes and styles | Corrección de las rutas añadidas y los estilos | 27/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | d1c743764741aa0c03f6086c93b0ba44a6337f02 | fixe(routes)::add routes fixed           | Corrección de las rutas añadidas          | 27/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | master                    | 5ce6a355dd938d7e741c411a5b95542144eb884d | fix(routes): :fixed tutor route           | Corrección de la ruta de tutor            | 27/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | master                    | dc7ddbe7eddb256eebfb91a3d3e4ed5dc0c93db9 | chore: added dependencies                  | Adición de las dependencias necesarias     | 27/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | 415699da160b5866a76d775df1d768db3e6a0c29 | fix(routes)::add fixed routes            | Corrección de las rutas.                  | 28/09/2023     |
| Aplicaciones-Web-SW53-Grupo-1/Web-Application     | develop                   | 7edaa5132ff6ae86736705292a3b8f40e57265e0 | fix(routes)::add fixed routes            | Corrección de las rutas                   | 28/09/2023     |

## Conclusiones

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880117959610441/image.png?width=596&height=559">

<img src="https://media.discordapp.net/attachments/783068752958717972/1149880189598322729/image.png?width=694&height=559">