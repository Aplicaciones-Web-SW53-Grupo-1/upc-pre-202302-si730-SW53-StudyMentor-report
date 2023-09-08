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

|   Members     |   User    |
|:-------------:|:---------:|
|---, ---                           |u202112936|
|Puican Salas, Kurt Matthews        |U202016643|
|Luyo Ramirez, Rafael Arturo        |u202115348|
|----, ----                         |u202110458|
|--, ---                            |u20201b895|

#### Ciclo 2023 - 02

<br><br>

## Registros de versiones del Informe

|   Version     |   Fecha   |   Autor   |   Descripción de la modificación|
|:-------------:|:---------:|:---------|:------------------------|
|1              |           |----|- Implementó  |
|1              |           |---|- Implementó  |
|1              | 31/08/23  |Luyo Ramirez |- Implementó 4.1, 4.2, 4.3, 4.8  |
|1              |           |--|- Implementó  |
|1              |           |--|- Implementó  |

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
      <img src="##" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="##" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
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