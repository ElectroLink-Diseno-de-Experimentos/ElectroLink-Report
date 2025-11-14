<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="upc-logo" width="120px" height="120px"/>
</p>

<h1 align="center">
    Universidad Peruana de Ciencias Aplicadas
</h1>

<h3 align="center">
    Carrera: Ingeniería de Software
    <br> <br>
    Curso: 1ASI0732 - Diseño de Experimentos de Ingeniería de Software
    <br> <br>
    Sección: 14652
    <br> <br>
    Profesor: Juan Antonio Flores Moroco
    <br> <br>
    Ciclo: 2025-20 
    <br> <br>
    Informe de TP
    <br> <br>
    Startup: HampCoders
    <br> <br>
    Producto: ElectroLink  
</h3>

<div align="center">
  
|             <div style="width:300px">Alumno</div>             | <div style="width:125px">Código</div> |
|:-------------------------------------------------------------:|:-------------------------------------------:|
|                 Kenyi Efrain Ramirez Cabrera                  |              U202220138           |
|                 Leandro Saul Contreras López                  |              U20231E215           |
|               Jefferson Ernesto Castro Pariona                |              U201822823           |
|                   Miguel Angel Gomez Hurtado                  |              u202220294           |             
|                                                               |                                   |

</div>

<div align="center"> Octubre 2025 </div>

<hr>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

| Versión | Fecha       | Autor(es)                                   | Descripción de modificación |
|---------|-------------|----------------------------------------------|------------------------------|
|   TB1   | 19/09/2025  | **Kenyi Efrain Ramirez Cabrera**              | Redacción del Capítulo I a V. Diseño de arquitectura usando *Domain-Driven Design*. Implementación inicial de la landing page. Documentación técnica de componentes. Diseño de historias de usuario. Coordinación general del enfoque técnico del proyecto. Correcciones y mejoras en el desarrollo frontend. |
|   TB1   | 19/09/2025  | **Leandro Saúl Contreras López**             | Elaboración de análisis competitivo y estrategias frente a competidores. Definición de *Lean UX Problem Statements* y *Assumptions*. Colaboración en entrevistas y registro de hallazgos. Implementacion y Mejorar dle Frontend. |
|   TB1   | 19/09/2025  | **Jefferson Ernesto Castro Pariona**           | Configuración del entorno de desarrollo. Gestión inicial del *Product Backlog*. Aportes en la estructura general del documento y lineamientos de SEO. Correciones de la landing page |
|   TB1   | 19/09/2025  | **Miguel Angel Gomez Hurtado**            | Diseño de *User Personas*, *User Task Matrix* y flujos de usuario. Desarrollo de prototipos web y guía de estilos visuales. Apoyo en estructura narrativa del documento. Mejoras y despliegue del backend. |
|   TP    | 10/10/2025  | **Miguel Angel Gomez Hurtado**            | Desarrollo de pruebas unitarias de Bounded Context Monitoring y pruebas de integración. Desarrollo de checkStyle de Monitoring. |
|   TP    | 10/10/2025  | **Kenyi Ramirez Cabrera**            | Implementación de elementos faltantes en algunas secciones. |



<hr>

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights  

**Enlace de la organización del proyecto**

- Organización GitHub: ElectroLink-Diseño de Experimentos: https://github.com/ElectroLink-Diseno-de-Experimentos
- Repositorio GitHub: ElectroLink: https://github.com/ElectroLink-Diseno-de-Experimentos/ElectroLink-Report
  

Insights del TB1

<br>

<a href="https://ibb.co/HDMHzSSS"><img src="https://i.ibb.co/WWd2yhhh/Insights.png" alt="Insights" border="0"></a>

<br>

<a href="https://ibb.co/kgGdWcFQ"><img src="https://i.ibb.co/TBwCFh5m/contri.png" alt="contri" border="0"></a><br>


<hr>

Insights del TP

<br>

[![image.png](https://i.postimg.cc/QMTwFQSg/image.png)](https://postimg.cc/PLd2c8gN)

<br>

<div style="page-break-after: always;"></div>

## Tabla de Contenidos

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
  - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
    - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
  - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
  - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
  - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
  - [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)
    - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6. RESTful API documentation](#526-restful-api-documentation)
    - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)
  - [6.1. Testing Suites & Validation](#61-testing-suites--validation)
    - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
    - [6.1.2. Core Integration Tests](#612-core-integration-tests)
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
    - [6.1.4. Core System Tests](#614-core-system-tests)
  - [6.2. Static testing & Verification](#62-static-testing--verification)
    - [6.2.1. Static Code Analysis](#621-static-code-analysis)
      - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)
      - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
    - [6.2.2. Reviews](#622-reviews)
- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
  - [7.1. Continuous Integration](#71-continuous-integration)
    - [7.1.1. Tools and Practices](#711-tools-and-practices)
    - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
  - [7.2. Continuous Delivery](#72-continuous-delivery)
    - [7.2.1. Tools and Practices](#721-tools-and-practices)
    - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
  - [7.3. Continuous deployment](#73-continuous-deployment)
    - [7.3.1. Tools and Practices](#731-tools-and-practices)
    - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
  - [8.1. Experiment Planning](#81-experiment-planning)
    - [8.1.1. As-Is Summary.](#811-as-is-summary)
    - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
    - [8.1.3. Experiment-Ready Questions.](#813-experiment-ready-questions)
    - [8.1.4. Question Backlog.](#814-question-backlog)
    - [8.1.5. Experiment Cards.](#815-experiment-cards)
  - [8.2. Experiment Design](#82-experiment-design)
    - [8.2.1. Hypotheses.](#821-hypotheses)
    - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
    - [8.2.3. Measures.](#823-measures)
    - [8.2.4. Conditions.](#824-conditions)
    - [8.2.5. Scale Calculations and Decisions.](#825-scale-calculations-and-decisions)
    - [8.2.6. Methods Selection.](#826-methods-selection)
    - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection.](#827-data-analytics-goals-kpis-and-metrics-selection)
    - [8.2.8. Web and Mobile Tracking Plan.](#828-web-and-mobile-tracking-plan)
  - [8.3. Experimentation](#83-experimentation)
    - [8.3.1. To-Be User Stories.](#831-to-be-user-stories)
    - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
- [Avance de Conclusiones, Bibliografía y Anexos](#avance-de-conclusiones-bibliografía-y-anexos)



 

<div style="page-break-after: always;"></div>

## Student Outcome 4 – Diseño de Experimentos

En esta sección se evidencia cómo las actividades realizadas en el **TB1** han contribuido al desarrollo del **Outcome 4 de ABET – EAC**, referido a la capacidad de planificar y gestionar proyectos de desarrollo de software utilizando metodologías y herramientas apropiadas. Cada integrante del equipo ha asumido responsabilidades clave que implicaron la definición de alcances, la organización de tareas y la aplicación de enfoques de gestión ágil. Estas acciones fortalecieron la habilidad del equipo para ejecutar el proyecto de manera coordinada y eficiente, cumpliendo con los objetivos y plazos establecidos.

*Planifica y gestiona proyectos de desarrollo de software utilizando metodologías y herramientas apropiadas.*

-----
| **Criterio específico**                                                                  | **Acciones realizadas (TB1)** | **Acciones realizadas (TP)** | **Conclusiones (TP)** |
|:-----------------------------------------------------------------------------------------| :--- | :--- | :--- |
| **Demuestra capacidad de planificar y gestionar proyectos de desarrollo de software.**   | **Kenyi Efrain Ramirez Cabrera**<br>- Redactó los capítulos iniciales del proyecto, estableciendo la estructura y el alcance del documento.<br>- Lideró la arquitectura del proyecto utilizando **Domain-Driven Design**, lo que sirvió como base para la planificación técnica.<br>- Gestionó la creación e implementación de la **landing page** y la **documentación técnica**, organizando las tareas de desarrollo *frontend*.<br>- Definió y gestionó las **historias de usuario**, aplicando metodologías ágiles para la planificación de tareas.<br><br>**Leandro Saúl Contreras López**<br>- Elaboró el **análisis competitivo** y las **estrategias**, lo cual formó parte de la planificación estratégica del proyecto.<br>- Definió los **Lean UX Problem Statements** y **Assumptions**, estableciendo la dirección del producto desde una perspectiva centrada en el usuario.<br>- Colaboró en la gestión de entrevistas y en el registro de hallazgos, aportando al levantamiento de requisitos del proyecto.<br>- Participó en la **implementación y mejoras del frontend**, gestionando las tareas de desarrollo asignadas.<br><br>**Jefferson Ernesto Castro Pariona**<br>- Configuró el **entorno de desarrollo**, un paso crítico en la fase de planificación del proyecto.<br>- Asumió la gestión inicial del **Product Backlog**, organizando y priorizando las tareas del equipo.<br>- Contribuyó a la estructura general del documento y a los lineamientos de **SEO**, asegurando que el proyecto cumpliera con los objetivos de visibilidad y calidad de la documentación.<br><br>**Miguel Angel Gomez Hurtado**<br>- **TB1:** Diseñó las **User Personas** y **User Task Matrix**, elementos clave para la planificación del producto y la experiencia de usuario.<br>- Desarrolló los **prototipos web** y la **guía de estilos**, gestionando el diseño visual del proyecto.<br>- Participó en las **mejoras y despliegue del backend**, asegurando el cumplimiento de las tareas de desarrollo *backend*. | **Kenyi Efrain Ramirez Cabrera**<br>- **Diseñó e implementó Pruebas Unitarias (JUnit/Mockito)** y **Pruebas de Integración y E2E (Karate)** para el BC **Assets** (Componentes e Inventario del Técnico).<br>- **Redactó las secciones de DevOps Practices (CI/CD)** y **Static Testing & Verification (Reviews)** del informe, formalizando las prácticas del equipo.<br><br>**Leandro Saúl Contreras López**<br>- **Diseñó e implementó Pruebas Unitarias/Integración (Karate)** y aplicó **Checklist de Calidad** para el BC **Service Design and Planning**.<br>- **Redactó las secciones de introducciones de Pruebas (Test Suite)** del informe, documentando la metodología de validación.<br><br>**Jefferson Ernesto Castro Pariona**<br>- **Diseñó e implementó Pruebas Unitarias/Integración (Karate)** y aplicó **Checklist de Calidad** para el BC **Profiles**.<br>- **Redactó las Conclusiones y Resúmenes Ejecutivos** del informe, sintetizando los hallazgos de cada capítulo.<br><br>**Miguel Angel Gomez Hurtado**<br>- **Diseñó e implementó Pruebas Unitarias/Integración (Karate)** para los BC **Monitoring** e **IAM** (Autenticación/Autorización).<br>- **Lideró la ejecución y el análisis de SonarQube/CheckStyle** para todos los *Bounded Contexts* Java.<br>- **Redactó las secciones de introducciones de Pruebas (Test Suite)** del informe, documentando la metodología de validación. | **TB1:** El equipo demostró una sólida capacidad de **planificación y gestión de proyectos**. La aplicación de **metodologías ágiles** como Lean UX y la gestión del Product Backlog permitió organizar las tareas de manera eficiente y adaptarse a los desafíos del proyecto. Cada miembro asumió responsabilidades claras que, al ser ejecutadas de forma coordinada, aseguraron el progreso y cumplimiento de los entregables iniciales, sentando una base robusta para las siguientes etapas del proyecto.<br><br>**TP:** La fase se centró en la **ejecución rigurosa del testing, la validación de calidad y la documentación formal**. La implementación de un **testing integral (Unitarias, Integración y E2E)** por *Bounded Context* y el uso de herramientas como **Karate, CheckStyle (liderado por Miguel) y SonarQube** confirmaron la adhesión a los estándares de **Clean Code**. La **redacción y formalización de las secciones técnicas (DevOps, Testing, Reviews)** evidenció una gestión efectiva del conocimiento y una madurez en las prácticas de ingeniería de *software* del equipo. |<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

Este capítulo proporciona una visión general del proyecto, incluyendo la problemática abordada, los objetivos planteados, la motivación del equipo y el alcance de la solución propuesta. Se establece el contexto en el que surge la necesidad de la plataforma ElectroLink, y se justifica su relevancia para los usuarios objetivo y el entorno actual.

<br>

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

HampCoders es una startup innovadora que se enfoca en el desarrollo de soluciones empleando una arquitectura orientada a servicios, haciendo uso de tecnologías open-source. Mediante esta startup, buscamos lograr conectar a los proveedores de componentes eléctricos con posibles clientes. Es por ello que presentamos el proyecto ElectroLink.

Misión: Nuestra misión es desarrollar una solución tecnológica innovadora que permita a las personas contactar con empresas proveedoras especializadas en electrónica, para prevenir o solucionar problemas en instalaciones eléctricas de manera efectiva, segura y legalmente correctas.

Visión: Nuestra visión es convertirnos en líderes globales en el desarrollo de tecnologías y plataformas eficientes y escalables, proporcionando herramientas que permitan conectar a los usuarios y empresas con proveedores especializados, para prevenir o solucionar instalaciones eléctricas ineficientes, transformando el entorno brindando calidad y seguridad.


### 1.1.2. Perfiles de Integrantes de equipo
| Miembros del equipo                                                                                                                                                                       | Codigo Estudiante | Descripcion            |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------| ---------------------- |
| Jefferson Ernesto Castro Pariona                                                                                                                                                          | U201822823            | descripcion | 
| Kenyi Efrain Ramirez Cabrera [![Whats-App-Image-2025-09-12-at-10-09-31-PM-1.jpg](https://i.postimg.cc/ZqgfRqwf/Whats-App-Image-2025-09-12-at-10-09-31-PM-1.jpg)](https://postimg.cc/5HB5Kfdv) | u202220138        | Soy Kenyi Ramirez, estudio la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy una persona comprometida y trabajadora. Poseo un nivel intermedio en los lenguajes C++, C#, Python, Java y HTML, además de algunos frameworks como Angular, Node.js y Vue, los cuales aplico para garantizar resultados efectivos en mis proyectos. | 
| Leandro Saúl Contreras Lopez	![Imagen del compañero](https://i.postimg.cc/FF86sBWr/Screenshot-2025-07-08-at-5-48-58-PM.png)                                                               | U20231E215        | Mucho gusto, soy Leandro Contreras, estudiante de la carrera de Ingeniería de Software en la UPC, sede San Miguel, tengo 19 años y estoy cursando el sexto ciclo académico. Me considero una persona adaptativa, perseverante y comprometida con lo que me propongo. En este proyecto tengo como objetivo buscar múltiples soluciones que beneficien a todo el grupo, por experiencia propia suelo trabajar de manera colaborativa y eficaz. Terminando la carrera de ingeniería, me gustaría estudiar una segunda carrera: Gastronomía y Gestión culinaria | 
| Miguel Angel Gomez Hurtado <img src="https://i.postimg.cc/0N1330v8/Miguel-Foto.png" alt="Miguel Angel Gomez Hurtado - Foto" style="display: block; margin-left: auto; margin-right: auto;" height="300"/> | u202220294            | Tengo 23 años y estoy estudiando la carrera de Ingeniería Informática. Me encuentro en mi segundo ciclo en la UPC Sede San Miguel. Soy una persona académica y siempre estoy abierto al diálogo. Me apasiona mi carrera y siempre estoy dispuesto a aprender sobre este curso para brindar a mis futuros usuarios un buen producto acorde a sus necesidades. | 
| Imagen del compañero                                                                                                                                                                      | codigo            | descripcion | 

<br> 

## 1.2. Solution Profile 

ElectroLink es una solución que busca conectar proveedores de componentes o servicios electrónicos con potenciales clientes que necesiten asesoramiento para realizar mantenimientos preventivos en sus hogares u oficinas. Nuestra plataforma busca exhibir a los proveedores con el fin de resolver la desconexión entre proveedores de componentes eléctricos y el mercado real y garantizar servicios seguros y eficientes dentro de los parámetros legales para los clientes dueños de hogares y PYMES.

### 1.2.1. Antecedentes y problemática

Con el propósito de obtener una comprensión más profunda de las necesidades de nuestros usuarios, hemos investigado sus antecedentes históricos y los desafíos que enfrentan mediante la metodología de las 5W`S y 2H`S. Este enfoque nos asegura que la información recopilada sea pertinente y nos permita desarrollar soluciones precisas y eficaces que satisfagan sus necesidades.

**What (Qué)**  
- ¿Cuál es el problema?
El problema radica en la dificultad que afrontan los usuarios al momento de encontrar proveedores técnicos eléctricos eficientes, seguros y certificados en base a las especificaciones que requieren según su situación. Esta situación puede agravarse por la falta de formación formal y de plataformas que garanticen la calidad del servicio, dentro de los parámetros establecidos por el gobierno.

- ¿Cuál es la relación con la persona en cuestión?
Este proyecto está directamente relacionado con los usuarios objetivo, puesto que actúa como intermediario entre estos y el proveedor del servicio de una manera rápida y efectiva. De la misma manera, se optimiza el tiempo de respuesta, garantizando que los problemas se resuelvan de forma eficiente, sin comprometer la calidad del servicio.


**When (Cuando)**  
- ¿Cuándo sucede el problema?
Los problemas relacionados con la dificultad de contactar con proveedores de garantía se manifiestan en situaciones como cortes de electricidad, costos de luz, instalaciones defectuosas o fuera de los parámetros legales, problemas con tomacorrientes, o incluso antes de una remodelación donde se necesita prevenir sobrecargas.

- ¿Cuándo utiliza el cliente el producto?
Lo usa en momentos críticos, cuando el fallo ya ocurrió, o de forma preventiva antes de hacer una instalación eléctrica o compra de componentes, de forma específica según  la situación a la que se enfrentan. 


**Where (Dónde)**  
- ¿Dónde está el cliente cuando usa el producto?
La solución puede ser usada por los usuarios en cualquier momento y lugares con alta demanda eléctrica, incluyendo así a usuarios independientes o empresas.

- ¿A dónde se dirige?
La solución está dirigida a aquellos usuarios que deseen prevenir problemas eléctricos asegurándose de obtener una instalación correcta y dentro de los parámetros permitidos, así como los que buscan solucionar algún problema eléctrico que se presente.

- ¿Dónde surge el problema?
Este problema ocurre en lugares con alta demanda eléctrica, como por ejemplo: hogares, centros educativos, oficinas, centros comerciales, entre otros, donde la sobrecarga o fallos eléctricos pueden generar inconvenientes significativos.

**Who (Quién)**
- ¿Quiénes están involucrados?
  Equipo: Aquellos encargados del desarrollo y soporte técnico de la solución, responsables de mantener y mejorar el sistema, asegurando un funcionamiento óptimo y la calidad del servicio.
  Usuarios: Aquellos que buscan soluciones ante problemas eléctricos o realizar instalaciones de manera segura.
  Proveedores: Aquellos que ofrecen servicios eléctricos, como componentes y/o instalaciones.

- ¿A quiénes le sucede el problema?
  Propietarios de viviendas: Aquellos que enfrentan fallos inesperados por problemas eléctricos o necesitan instalaciones de forma segura y eficiente en sus hogares.
  Propietarios de negocios y empresas: Los encargados de gestionar y renovar lugares con alta demanda eléctrica, que requieren soluciones fiables para sus instalaciones y/o operaciones diarias.
  Centros educativos: Instituciones que requieren mantener sus instalaciones eléctricas en óptimas condiciones, para garantizar la seguridad del alumnado y personal.

- ¿Quién lo utilizará?
  El producto se dirige a una amplia gama de personas, entre las cuales destacan el cliente final y el proveedor del servicio.El cliente final busca una solución rápida y confiable para sus problemas eléctricos, mientras que el proveedor del servicio se beneficia al obtener nuevos clientes y mejorar su visibilidad.


**Why (Por qué)**
- ¿Cuál es la causa del problema?
  La falta de plataformas que conecten de manera eficiente a proveedores eléctricos con usuarios, sumado a la poca formalización del rubro. Los usuarios a menudo no saben cómo identificar técnicos confiables, lo que incrementa el riesgo de contratar profesionales no calificados. Además, el mal manejo de instalaciones eléctricas es una preocupación constante, generando riesgos frecuentes para la seguridad.


**How (Cómo)**
- ¿En qué condiciones los clientes usan nuestro producto?
  Se usa en situaciones donde requieren una solución eficiente y confiable para problemas eléctricos, ya sea durante una emergencia o de manera preventiva antes de una instalación. La solución se emplea en entornos domésticos o laborales.

- ¿Cómo nos conocieron los compradores?
  Nos conocieron a través de campañas de marketing digital, recomendaciones de amigos, búsquedas en internet sobre soluciones rápidas para problemas eléctricos y publicidad en redes sociales.

- ¿Cómo prefieren los lectores acceder a nuestro contenido?
  Los usuarios prefieren acceder a nuestra solución a través de una plataforma web o aplicación móvil, de fácil navegación y diseño intuitivo, que les permita conectarse con proveedores de servicio eléctrico en cualquier momento y lugar.

- ¿Qué llevó a la persona a llegar a esta situación?
  Cuando enfrenta un problema eléctrico, ya sea por una falla inesperada o por la necesidad de realizar una instalación, se encuentra en la búsqueda de soluciones rápidas, confiables y certificadas para evitar riesgos y asegurar el correcto funcionamiento de las instalaciones eléctricas.

**How much (Cuánto)**
- En 2021, el 45,3% de los hogares con acceso a la red pública de energía eléctrica experimentaron cortes o interrupciones.
- En 2021, el 45,3% de los hogares con acceso a la red pública de energía eléctrica experimentaron cortes o interrupciones.
- Estudios indican que departamentos como Áncash, Arequipa, Cusco, Huánuco, Madre de Dios, Pasco y Puno presentan altos porcentajes de hogares con experiencias negativas en la calidad del servicio eléctrico.
- En 2022, la frecuencia promedio de interrupciones fue de 9,8 veces, con mayor incidencia en el segmento de distribución eléctrica.

### 1.2.2. Lean UX Process

Según Pragma (2021), el proceso Lean UX es la mezcla de metodologías ágiles y temas de usabilidad, donde se prioriza la experiencia de usuario por la creación de un producto. Teniendo en cuenta ello, hemos elaborado nuestro Lean UX process basándonos en sus cuatro pilares principales: problem statements, assumptions, hypothesis y canvas.

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement#1** 
<br>
Nuestra plataforma busca conectar a dueños de hogares urbanos con proveedores técnicos eléctricos certificados, garantizando servicios seguros y eficientes dentro de los parámetros legales.

Hemos identificado que los dueños de hogares urbanos enfrentan dificultades para encontrar proveedores confiables, lo que genera riesgos en sus instalaciones y retrasos en la solución de problemas críticos.Esta situación no solo pone en riesgo la seguridad de hogares y negocios, sino que también genera costos adicionales por reparaciones mal ejecutadas y pérdidas económicas por interrupciones prolongadas.

Ante este desafío, surge la pregunta: ¿Cómo podemos garantizar que los usuarios encuentren proveedores eléctricos certificados de manera rápida y confiable, reduciendo riesgos y mejorando la eficiencia en la solución de problemas?

**Problem Statement #2** 
<br>
Nuestra plataforma busca resolver la desconexión entre proveedores de componentes eléctricos y el mercado real, eliminando la dependencia de canales informales y recomendaciones causales que limitan su crecimiento.

Hemos identificado que los proveedores de componentes eléctricos enfrentan dificultades para encontrar clientes de forma constante, lo que genera un aumento considerable de informalidad en el sector eléctrico.Esta situación los obliga a operar con márgenes reducidos debido a la competencia desleal de productos pirata o de baja calidad. Muchos dependen exclusivamente de ventas por recomendación o redes sociales, sin acceso a herramientas profesionales de gestión comercial.

Ante este desafío, surge la pregunta clave: ¿Cómo podemos crear un puente digital que permita a los proveedores de componentes eléctricos ampliar su mercado, garantizar ventas recurrentes y competir en igualdad de condiciones, rompiendo así el ciclo de informalidad en el sector?

#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes:**  
1. Mis clientes necesitan una solución efectiva y accesible para conectar con proveedores de calidad que les den los productos tecnológicos y eléctricos que requieren en la instalación eléctrica que quieren colocar o corregir.

2. Estas necesidades se pueden resolver con una solución tecnológica que aproveche los avances de software en avances de análisis de datos, plataformas digitales como una web distribuida bajo una arquitectura orientada a servicios realizada con tecnologías open-source, para facilitar la conexión entre clientes y proveedores.

3. Mis clientes iniciales serán propietarios de viviendas, propietarios de negocios y empresas y centros educativos que requieren soluciones rápidas y seguras para sus problemas eléctricos.

4. El valor número 1 que un cliente quiere de mi servicio es la garantía de contar con proveedores eléctricos certificados y seguros, que puedan brindar confianza, cumplimiento normativo y atención oportuna, a través de una plataforma confiable y de alta calidad técnica.

5. El cliente también puede obtener estos beneficios adicionales: reducción de riesgos eléctricos, ahorro de tiempo al evitar búsquedas extensas, seguridad de contratar personal con respaldo, posibilidad de programar servicios preventivos y seguimiento del servicio en tiempo real.

6. Vamos a adquirir la mayoría de los clientes a través de estrategias de marketing digital, incluyendo redes sociales, publicidad segmentada, campañas de correo electrónico, e invitaciones a posibles usuarios a conferencias, charlas informativas y eventos de lanzamiento.
7. Haré dinero a través de suscripciones mensuales pagadas por los proveedores, quienes tendrán acceso exclusivo a nuestra red de usuarios, lo que les permitirá ofrecer sus servicios de manera directa y personalizada dentro de la plataforma, maximizando su visibilidad y generando oportunidades de negocio.

8. Mi competencia principal en el mercado serán empresas establecidas como Thumbtack, Handy y TaskRabbit, los cuales ofrecen un medio que conecta a clientes con profesionales en diversas áreas, incluyendo la eléctrica.

9. Los venceremos debido a nuestro enfoque único en la verificación rigurosa de técnicos certificados, asegurando la seguridad y confiabilidad de cada servicio. Además, ofrecemos una experiencia personalizada que se adapta a las necesidades específicas de cada usuario, brindando soporte en tiempo real para resolver dudas y ofrecer soluciones inmediatas en momentos críticos. Todo esto, complementado con una plataforma fácil de usar.

10. Mi mayor riesgo es que los usuarios desconfíen del servicio o que los proveedores no cumplan con los estándares prometidos, afectando la reputación de la plataforma.

11. Resolveremos esto a través de un riguroso proceso de validación de proveedores, con revisión de certificaciones, calificaciones públicas, sistema de penalización a técnicos mal evaluados y atención al cliente activa, teniendo en cuenta las restricciones legales en instalaciones eléctricas.

12. ¿Qué otras suposiciones tenemos?<br>
Otras suposiciones que debemos considerar incluyen la disponibilidad de proveedores dispuestos a suscribirse a nuestra plataforma, la capacidad de escalar el servicio a nivel regional o nacional, y la aceptación de los usuarios de la plataforma como una alternativa confiable y preferida frente a métodos tradicionales de búsqueda de proveedores eléctricos. <br> <br>
¿Eso, si se prueba que es falso, causará que nuestro negocio / proyecto no funcione? <br>
Si estas suposiciones resultan ser falsas, podríamos enfrentar obstáculos importantes. Si no logramos atraer suficientes proveedores, la plataforma no sería atractiva ni útil para los usuarios, lo que pondría en riesgo nuestra capacidad de ofrecer un servicio integral. Si la aceptación de la plataforma no es lo suficientemente alta, perderíamos relevancia frente a métodos tradicionales, lo que podría limitar nuestro crecimiento.

**Users:**  
Nuestros usuarios principales son:
- Propietarios de hogares urbanos
- Dueños PYMES u oficinas
- Proveedores de componentes o servicios eléctricos certificados

**User Outcomes:**  
**¿Quién es el usuario?**
-   Nuestros usuarios principales son propietarios de hogares urbanos, dueños PYMES u oficinas y proveedores de componentes o servicios eléctricos certificados.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**
-   Hemos detectado 2 posibles problemas , el primero es la dificultad por parte de los propietarios y dueños de PYMES u oficinas para encontrar proveedores confiables dado que no ofrecen las garantías necesarias.Por otro lado, el segundo problema identificado va por parte de los proveedores de componentes o servicios electricos ya que  enfrentan dificultades para encontrar clientes de forma constante.El primer problema se resolvería por medio de nuestra plataforma que mostrará y recomendará a proveedores certificados que se adecuen a las necesidades del usuario.El segundo problema se resolvería por medio de la exposición que le brindaremos a los proveedores en nuestra plataforma permitiéndole conectarse con potenciales clientes.


**¿Qué características son importantes?**

-   **Para propietarios y dueños de PYMES u oficinas:** 
    - Búsqueda y filtrado de técnicos certificados. 
    - Sistema de reseñas y calificaciones transparente.
    - Opción de programación de servicios preventivos.
    - Seguimiento en tiempo real del servicio.
    - Información sobre consumo eficiente.

-   **Para proveedores:**
    - Perfil verificable con certificaciones.
    - Acceso a una red de clientes potenciales.
    - Herramientas de gestión (agenda, historial de servicios, pagos integrados).
    - Notificaciones de oportunidades de trabajo.
    - Protección contra la competencia desleal.
    

**¿Dónde encaja nuestro producto en su trabajo o vida?**

**Nuestro producto es utilizado:**

- Cuando los propietarios de hogares enfrentan problemas eléctricos urgentes, necesitan mantenimiento preventivo o requieren asesoría para optimizar el consumo de energía. La plataforma evita el estrés de buscar técnicos de manera informal y les da seguridad al garantizar que los proveedores están validados.

- En el caso de proveedores de componentes o servicios eléctricos, la plataforma se integra como su principal canal de clientes, reemplazando métodos tradicionales como el boca a boca o las redes sociales. Les permite gestionar su negocio de manera más profesional, aumentar su visibilidad y acceder a oportunidades de negocio recurrentes sin depender de la informalidad.


**¿Cuándo y cómo es usado nuestro producto?**

**Propietarios y dueños de PYMES u oficinas:**  
- **Cuándo:** En emergencias eléctricas, mantenimiento preventivo o al necesitar asesoría técnica.  
- **Cómo:** Acceden a la plataforma, buscan técnicos cercanos, comparan perfiles, contratan y califican el servicio.  

**Proveedores:**  
- **Cuándo:** Cuando buscan nuevos clientes o gestionan sus servicios.  
- **Cómo:** Crean su perfil verificable, reciben solicitudes, gestionan citas y pagan suscripciones por acceso premium.  

**¿Cómo debe verse nuestro producto y cómo comportarse?**
-Se utiliza en momentos críticos (fallas, cortes de electricidad, sobrecargas) y también de forma preventiva (remodelaciones, instalación de nuevos equipos, revisiones anuales).Asimismo , se puede acceder desde dispositivos móviles o web, en el hogar, oficina o incluso en movimiento.También podría ser usado rápidamente cuando se requiere soporte urgente, o planificadamente para programar servicios.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Creemos que** al ofrecer una plataforma digital que verifique rigurosamente a técnicos eléctricos, los propietarios de hogares urbanos y dueños de PYMES u oficinas confiarán en nuestro servicio para resolver sus problemas eléctricos de manera rápida y segura.

**Sabremos que** hemos tenido éxito cuando el 70% de los usuarios que contratan un servicio a través de la plataforma lo califican con 4 o 5 estrellas, demostrando satisfacción con la calidad y confiabilidad de los proveedores.

**Creemos que** los proveedores de servicios eléctricos se suscribirán a nuestra plataforma si les garantizamos acceso a clientes recurrentes y herramientas profesionales de gestión (agenda, pagos, historial).

**Sabremos que** hemos tenido éxito cuando el 60% de los proveedores en prueba gratuita se conviertan en suscriptores pagos y mantengan una tasa de renovación superior al 80% después de 3 meses.


**Creemos que** al conectar usuarios con técnicos certificados, disminuirán los problemas eléctricos recurrentes en sus hogares o negocios.

**Sabremos que** hemos tenido éxito cuando los usuarios reportan una "mejoría notable" en sus instalaciones y prevenciones eléctricas después de usar servicios de la plataforma.Los casos de "reparaciones mal hechas" mencionados por usuarios disminuyen significativamente en los comentarios.


**Creemos que** los usuarios encontrarán más conveniente usar nuestra plataforma que buscar recomendaciones personales o técnicos por redes sociales.

**Sabremos que** hemos tenido éxito cuando los usuarios expresan que la plataforma les "ahorra tiempo" en comparación con buscar técnicos por su cuenta.Más de la mitad de los usuarios activos prefieren la plataforma para futuras necesidades eléctricas.

**Creemos que** la plataforma puede expandirse a regiones con altos índices de informalidad en servicios eléctricos, replicando el éxito del mercado inicial.

**Sabremos que** hemos tenido éxito cuando nuevas ciudades alcancen el 60% del volumen de transacciones de la región pionera en un plazo de 6 meses, con un crecimiento orgánico del 20% mensual.

#### 1.2.2.4. Lean UX Canvas
<img src="https://i.imgur.com/OD3PmHm.png"/>

<hr>

## 1.3. Segmentos Objetivos

En esa sección se presentaran los segmentos objetivos encontrados

Nuestros usuarios principales son propietarios de hogares urbanos, dueños PYMES u oficinas y proveedores de componentes o servicios eléctricos certificados

**Segmento objetivo #1: Propietarios de hogares urbanos**

Aspectos demográficos:

- Sexo: Masculino y femenino
- Edades: Entre 25 y 60 años
- Nivel socioeconómico: Medio a Medio-alto
  
Aspectos geográficos:

- Zona geográfica en la que viven: Urbana, en ciudades de tamaño medio a grande
- Residen principalmente en: Zonas residenciales o condominios dentro de áreas urbanizadas
  
Aspectos psicográficos:

- Valoran el confort, la eficiencia y la seguridad en el hogar.
- Buscan soluciones tecnológicas que optimicen el uso de recursos eléctricos.
- Tienen interés en el mantenimiento preventivo y la mejora continua de sus viviendas.

**Segmento objetivo #2: Dueños PYMES u oficinas**

Aspectos demográficos:

- Sexo: Masculino y femenino
- Edades: Entre 28 y 55 años
- Nivel socioeconómico: Medio-alto
  
Aspectos geográficos:

- Zona geográfica en la que viven: Urbana
- Residen principalmente en: Zonas residenciales o condominios dentro de áreas urbanizadas
  
Aspectos psicográficos:

- Buscan optimizar los costos operativos y mejorar la eficiencia de sus instalaciones.
- Valoran soluciones tecnológicas que automaticen procesos de búsqueda y compra de componentes eléctricos para reducir y optimizar el consumo de recursos.
- Tienen mentalidad emprendedora y están abiertos a innovaciones que les den ventaja competitiva.

**Segmento objetivo #3: Proveedores de componentes o servicios eléctricos certificados**

Aspectos demográficos:

- Sexo: Masculino y femenino
- Edades: Entre 25 y 55 años
- Nivel socioeconómico: Medio a medio-alto
  
Aspectos geográficos:

- Zona geográfica en la que trabajan: Urbana, semi urbana e industrial
- Residen principalmente en: Regiones con alta demanda de servicios eléctricos (ciudades en expansión, polos industriales, etc.)
  
Aspectos psicográficos:

- Buscan aumentar su visibilidad y captar más clientes de forma digital.
- Están interesados en plataformas que les faciliten la gestión de pedidos o contactos comerciales.
- Valoran pertenecer a una red confiable de profesionales del rubro eléctrico.
- Están enfocados en el crecimiento profesional y la fidelización de clientes.

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

Aquí se describe el proceso de levantamiento y análisis de requerimientos funcionales y no funcionales del sistema. Incluye las técnicas utilizadas (entrevistas, encuestas, historias de usuario), los perfiles de usuario identificados y las prioridades del negocio. Se documentan las necesidades desde la perspectiva de los stakeholders, con énfasis en la trazabilidad y validación de requisitos clave.

<br>

## 2.1. Competidores

Hoy en día el competitivo mercado digital en la contratación de servicios, existen diversas empresas importantes que ofrecen soluciones en áreas como reparaciones, mantenimiento y tareas domésticas. Entre los competidores más destacados se encuentran Thumbtack, Handy y TaskRabbit

* **Thumbtack:**

Es una plataforma en línea que conecta a personas que necesitan servicios locales con profesionales que los ofrecen. Funciona como un marketplace donde puedes buscar desde plomeros, electricistas entre muchos otros.

Así es como funciona:

1. El cliente publica un proyecto explicando qué necesita

2. Los profesionales que están registrados en esa categoría y área geográfica reciben una notificación.

3. Los profesionales interesados envían cotizaciones o propuestas al cliente.

4. El cliente elige al profesional que mejor se adapte a su presupuesto y necesidades.

Es popular en Estados Unidos y suele ser útil para freelancers y pequeñas empresas

* **Handy:**

A diferencia de Thumbtack, Handy no te muestra varios profesionales para que elijas, sino que ellos se encargan de asignarte uno basado en disponibilidad y ubicación.

Especialidad: Servicios para el hogar (limpieza, montaje de muebles, plomería, electricidad, mudanzas, etc.).

Cómo funciona: Los clientes reservan directamente desde la app o el sitio web, eligen fecha/hora y el servicio que necesitan, y Handy asigna automáticamente a un profesional disponible.

Ubicación: Opera principalmente en EE. UU., Canadá y Reino Unido.

* **TaskRabbit:**

Es una plataforma donde puedes contratar “taskers” (personas que hacen tareas). Estos operan un mercado en línea que con la demanda local, permite a las personas encontrar ayuda con tareas que incluyen:

\+Montaje de muebles (especialmente de IKEA, ya que tienen una alianza).

\+Mudanzas y cargado de cosas pesadas.

\+Limpieza.

\+Reparaciones menores en el hogar.

\+Hacer compras o entregas.

\+Colgar cuadros, instalar estanterías, etc.

Cómo funciona TaskRabbit: 

1. Buscas el tipo de tarea que necesitas hacer.

2. Elige a un tasker basado en su perfil, tarifas por hora, y reseñas.

3. Agendas el servicio directamente con esa persona, eligiendo la fecha y la hora.

4. Pagas a través de la plataforma cuando el trabajo está completo.

### 2.1.1. Análisis competitivo

En esta sección, el equipo presenta el analisis competitivo 

| Competitive Analysis Landscape |  |  |  |  |  |
| ----- | :---- | :---- | :---- | :---- | :---- |
| ¿Por qué llevar a cabo este análisis |  | Porque  necesitamos identificar fortalezas, debilidades y diferenciadores clave frente a plataformas similares para definir la estrategia competitiva de ElectroLink. |  |  |  |
|  |  |  Necesitamos Adaptarnos a las tendencias del mercado |  |  |  |
|   |   | ElectroLink | Thumbtack | Handy | TaskRabbit |
| Perfil | Overview |  Plataforma especializada en instalaciones y mantenimiento eléctrico legal y seguro. Conecta a clientes con proveedores certificados, ofreciendo asesoría técnica, prevención de riesgos y seguimiento en tiempo real.  |  Marketplace general de servicios donde los usuarios pueden encontrar profesionales para tareas como reparaciones |  Plataforma centrada en tareas del hogar como limpieza, montaje de muebles y algunas reparaciones menores |  Conecta personas con taskers para tareas del hogar como mudanzas, reparaciones menores, compras y más. |
|  | Ventaja competitiva ¿Qué valor ofrece a los clientes? | Instalaciones y mantenimiento eléctrico general con proveedores certificados. Servicio legal, seguro y con asesoría técnica. | Ofrece una amplia variedad de servicios, pero sin enfoque especializado. | Servicios de hogar bajo demanda. Asignación automática. | Contratación rápida para tareas específicas, con perfiles seleccionables. |
| Perfil de Marketing | Mercado objetivo | Hogares, oficinas, escuelas y PYMES urbanas que requieren instalaciones o mantenimiento eléctrico confiable. |  Clientes generales que necesitan servicios variados (hogar, eventos, clases, etc.). |  Personas que requieren limpieza, montaje o reparaciones domésticas. |  Hogares que requieren tareas prácticas como mudanza, limpieza, montaje, etc. |
|  | Estrategias de marketing |  Alianzas con proveedores certificados, educación sobre mantenimiento eléctrico. |  Publicidad digital, visibilidad en buscadores, reviews de usuarios. |  Integración con IKEA, marketing por conveniencia y rapidez. |  Visibilidad en buscadores con una app amigable y con integración con IKEA |
| Perfil de productos | Productos & Servicios | Instalación de componentes, mantenimiento general, diagnósticos técnicos y asesoría normativa. |  Servicios generales (fotografía, plomería, eventos, clases, etc.). |  Limpieza, fontanería, montaje, electricidad básica, mudanza. |  Montaje de muebles, limpieza, ayuda con tareas, mudanza. |
|  | Precios y Costos |  Costos por servicio y suscripción mensual para monitoreo/prevención. | Los profesionales establecen precios. Thumbtack cobra parte de la comisión |  Precio fijo por servicio. Handy toma parte de la comisión. |  Costo por hora según la tarea deseada. Taskrabbit cobra una comisión al profesional. |
|  | Canales de distribución (Web y/o Móvil) |  Plataforma web \+ app móvil (foco en experiencia técnica y educativa) |  Web \+ app móvil. |  Web \+ app móvil. |  Web \+ app móvil. |
| Análisis SWOT | Fortalezas | Especialización en electricidad, asesoría legal, prevención de riesgos y red de técnicos certificados. |  Variedad de servicios, alta visibilidad, gran base de usuarios. |  Rapidez de reserva por sus procesos automatizados. |  Facilidad para elegir trabajadores, buena reputación por las tareas simples. |
|  | Debilidades | Somos nuevos en el mercado y tenemos una dependencia de proveedores certificados: |  No tiene enfoque especializado, experiencia muy generalista. Puede ser complicado encontrar personal especializado. | Tiene poca personalización al ser todo generalmente automático |  Algunos trabajadores no están certificados. Esto puede variar la calidad de los servicios. |
|  | Oportunidades |  Alianzas con aseguradoras, certificaciones oficiales, posible expansión a smart energy, estos servicios están poco atendidos. |  Ampliar a servicios técnicos más especializados. |  Mejorar procesos de selección de profesionales a través de una expansión hacia servicios técnicos especializados. |  TaskRabbit podría asociarse con marcas de smart home (como Google Nest, Philips Hue, etc.) para ofrecer instalación y soporte técnico |
|  | Amenazas |  Falta de confianza inicial. Si no se mantiene un buen control o evaluación a los proveedores eléctricos puede afectar la experiencia del cliente. |  Tiene una gran saturación del mercado y competencia entre profesionales. |  Problemas con calidad inconsistente del servicio dado que los usuarios no eligen al profesional |  Cada vez más personas contratan técnicos y ayudantes directamente por redes como Facebook Marketplace. Lo que hace más difícil estar en el mercado. |

### 2.1.2. Estrategias y tácticas frente a competidores

Para lograr enfrentar a nuestros competidores como Thumbtack, Handy y TaskRabbit. Nuestro proyecto ElectroLink tendrá una serie de estrategias y tácticas sobre la calidad del servicio, confianza, y especialización en el sector de servicios electrónicos y de mantenimiento.

#### **1\. Estrategia de diferenciación especializandonos en sistemas eléctricos**

Plataformas como Thumbtack y TaskRabbit, que abarcan una amplia gama de servicios, ElectroLink se enfocará en servicios de mantenimiento preventivo y reparación de sistemas eléctricos para hogares y empresas. Esta especialización nos permitirá destacar como una solución confiable en el mercado..

#### **2\. Garantía de seguridad y legalidad en todos los servicios**

ElectroLink implementará un sistema de certificación en el cual los proveedores que estén en la plataforma sean realizados por profesionales certificados y con licencias. Además, se garantizará que todos los servicios cumplan con los estándares legales y normativos del sector eléctrico.

#### **3\. Precios transparentes y competitivos**

A diferencia de Thumbtack, el cual utiliza un modelo de pago basado en leads, ElectroLink ofrecerá un modelo de precios transparente y competitivo donde los usuarios y proveedores tengan conocimiento sobre los costos. También se implementará un sistema de suscripción o tarifas planas para trabajos de mantenimiento preventivo, lo que brinda seguridad a los clientes.

## 2.2. Entrevistas

De acuerdo con Easwaramoorthy y Zarinpoush (2006), las entrevistas son un método de investigación, en el que se lleva a cabo “una conversación para recolectar información”. En esta, se realizan una serie de preguntas sobre el agente que queremos llegar a conocer mejor y profundizar en su sentir y punto de vista. Para HampCoders, la información recogida a través de las entrevistas es esencial para identificar cómo ElectroLink aportaría a solucionar el problema relacionado a la instalación y mantenimiento preventivo sobre el consumo de energía, en qué medida y en qué aspectos específicos. Por ello, realizamos un total de 3 entrevistas por segmento. Todas las entrevistas se realizaron a larga distancia (Google Meet, Zoom y Discord), y de manera presencial, en un espacio cómodo y silencioso y dentro del ámbito informal. 

### 2.2.1. Diseño de entrevistas

**Segmento #1: Propietarios de hogares urbanos:**

**Preguntas principales:**
-   ¿Cómo te sientes normalmente cuando surge un problema eléctrico en tu casa, como un corte de luz o un tomacorriente que no funciona?
-   ¿Qué haces normalmente cuando necesitas encontrar a alguien que repare o revise una instalación eléctrica en tu hogar?
-   ¿Qué tan fácil o difícil te resulta encontrar técnicos eléctricos en quienes puedas confiar?
-   ¿Cuando has contratado un servicio eléctrico antes, ¿qué fue lo que más te preocupó?
-   ¿Qué cosas valoras más cuando contratas a alguien para que trabaje en tu casa (puntualidad, certificación, costo, rapidez)?
-   ¿Con qué frecuencia tomas medidas preventivas para evitar problemas eléctricos en tu hogar?
-   ¿Te ha pasado que una instalación mal hecha haya causado problemas luego? ¿Cómo lo resolviste?
-   ¿Qué importancia le das a que un servicio eléctrico esté dentro de los parámetros legales o normativos?
-   ¿Te interesaría usar una plataforma que conecte con proveedores verificados para servicios eléctricos en tu zona? ¿Por qué?
-   ¿Qué funcionalidades crees que harían esa plataforma útil para ti en el día a día?

**Preguntas complementarias:**
-   ¿Qué sueles buscar en internet cuando tienes dudas sobre una falla eléctrica?
-   ¿Cuánto confías en las recomendaciones de redes sociales o conocidos para encontrar técnicos?
-   ¿En qué momentos específicos crees que te sería más útil tener acceso rápido a un proveedor certificado?
-   ¿Te sentirías cómodo usando una plataforma para agendar mantenimientos eléctricos preventivos?

**Segmento #2: Dueños de PYMES u oficinas:**

**Preguntas principales:**
-   ¿Qué tipo de instalaciones eléctricas utilizas actualmente en tu negocio u oficina?
-   ¿Qué tan seguido te has enfrentado a fallas eléctricas en tus operaciones diarias?
-   ¿Cómo manejas actualmente el mantenimiento eléctrico de tu empresa? ¿Lo haces tú o lo delegas?
-   ¿Qué impacto tiene una falla eléctrica en tu productividad o en la atención al cliente?
-   ¿Qué criterios tomas en cuenta al contratar a un proveedor eléctrico para tu negocio?
-   ¿Has tenido malas experiencias con servicios técnicos eléctricos? ¿Qué aprendiste de esas situaciones?
-   ¿Qué tan importante es para ti que los proveedores cumplan con normativas legales y ofrezcan garantía?
-   ¿Te sentirías cómodo usando una plataforma que te conecte directamente con proveedores certificados?
-   ¿Qué funcionalidades esperarías de esa plataforma para que realmente te ayude a ahorrar tiempo y dinero?
-   ¿Crees que una herramienta así te daría una ventaja competitiva frente a otros negocios?

**Preguntas complementarias:**
-   ¿Qué sueles hacer cuando necesitas encontrar un componente eléctrico específico para tu empresa?
-   ¿Qué herramientas digitales usas actualmente para gestionar el mantenimiento o las instalaciones eléctricas de tu negocio?
-   ¿Dónde buscarías una solución que reduzca riesgos y mejore la eficiencia energética en tu negocio?
-   ¿Te sentirías más confiado si pudieras ver opiniones, calificaciones y certificaciones de los proveedores antes de contratarlos?

**Segmento #3: Proveedores de componentes o servicios eléctricos certificados:**

**Preguntas principales:**
-   ¿Cómo te sientes actualmente con la forma en que consigues clientes para tus servicios eléctricos?
-   ¿Qué estrategias usas para dar a conocer tu trabajo y atraer nuevos clientes?
-   ¿Qué dificultades enfrentas al competir con proveedores no certificados o informales?
-   ¿Qué tan fácil es para ti comunicar la calidad y legalidad de tu trabajo a los potenciales clientes?
-   ¿Cómo manejas la gestión de pedidos o solicitudes de trabajo actualmente?
-   ¿Qué importancia tiene para ti pertenecer a una red de profesionales avalados o certificados?
-   ¿Qué tanto te ayudaría una plataforma que te permita mostrar tu experiencia, certificaciones y opiniones de clientes?
-   ¿Estarías dispuesto a pagar una suscripción mensual si eso te garantiza mayor visibilidad y más clientes? ¿Por qué?
-   ¿Qué funcionalidades crees que te facilitarán la gestión comercial desde una app o plataforma?
-   ¿Cómo crees que cambiaría tu negocio si pudieras digitalizar la forma en que conectas con clientes?

**Preguntas complementarias:**
-   ¿Dónde públicas actualmente tus servicios (Facebook, grupos, WhatsApp, boca a boca)?
-   ¿Has probado plataformas para ofrecer tus servicios? ¿Cómo fue la experiencia?
-   ¿Qué herramientas digitales usas (si usas alguna) para organizar tus trabajos y pedidos?
-   ¿Qué tan dispuesto estarías a formar parte de una comunidad de proveedores certificados con estándares comunes?

<hr>

### 2.2.2 Segmentación de Entrevistas

### Segmento #1: Propietarios de hogares urbanos

**Entrevista: Mari Vallejos**  
- **Sexo:** Femenino  
- **Edad:** 30  
- **Link:** https://www.youtube.com/watch?v=nTeFYzyawYk
- **Inicia en:** 0:06  
- **Duración:** 6:35
  
<img src="https://i.postimg.cc/k4ZTG2y1/Screenshot-2025-07-08-at-5-52-09-PM.png"/>

**Resumen:**  
Mari es ama de casa y pasa la mayor parte del tiempo en su hogar, lo que la hace responsable de todos los asuntos domésticos. Cuando surge un problema eléctrico, como un corte de luz o un enchufe dañado, experimenta ansiedad por no saber cómo resolverlo. Su reacción suele ser buscar ayuda en redes sociales, especialmente en Instagram o grupos vecinales, basándose en recomendaciones y comentarios.

Le preocupa que el servicio sea de calidad, que el proveedor sea puntual, rápido y comprometido, ya que valora que el problema se resuelva de manera eficaz. Sin embargo, no realiza mantenimientos preventivos por falta de conocimiento. Aunque sabe que las normativas legales son importantes, su prioridad es que el trabajo funcione bien.

Mari muestra interés en una plataforma como **ElectroLink**, siempre que incluya proveedores verificados y reseñas reales. Sugiere que la plataforma tenga filtros por experiencia, horario, costo y calificaciones para facilitar su uso.

---

### Segmento #2: Dueños de PYMES u oficinas

**Entrevista : Piero Tenorio**  
- **Sexo:** Masculino  
- **Edad:** 26  
- **Link:** https://www.youtube.com/watch?v=_z8UNTi_cmA
- **Inicia en:** 0:01  
- **Duración:** 9:54
<img src="https://i.postimg.cc/jSKZD0zb/Screenshot-2025-07-08-at-5-53-11-PM.png"/>

**Resumen:**  
Piero es dueño de una pequeña empresa de autopartes con varias sucursales. Su negocio depende de equipos eléctricos como computadoras, escáneres, cámaras de seguridad y luces. Las fallas eléctricas, aunque poco frecuentes, afectan la productividad al interrumpir los sistemas de inventario, lo cual puede hacer que los clientes se vayan.

Aunque intentó manejar el mantenimiento por sí mismo, ahora lo delega pero sin un plan definido. No realiza mantenimiento preventivo y reconoce que esto es un riesgo. También conoce casos de técnicos no confiables, por lo que valora servicios con garantía y cumplimiento normativo.

Está dispuesto a usar **ElectroLink** si ofrece proveedores certificados, reseñas, calificaciones y funcionalidades como el registro de consumo eléctrico, alertas de fallas y recomendaciones de mejora.


**Entrevista : Brian Cerna**  
- **Sexo:** Masculino  
- **Edad:** 25  
- **Link:** https://www.youtube.com/watch?v=m8Q_n7i_xEk
- **Inicia en:** 0:01  
- **Duración:** 6:16
<img src="https://i.postimg.cc/yNpPpD21/Screenshot-2025-07-08-at-5-53-57-PM.png"/>

En esta entrevista se conversó con Brian Cerna, representante del sector de dueños de pymes u oficinas, con el objetivo de conocer su experiencia y necesidades respecto a las instalaciones eléctricas en su negocio. Brian indicó que en su oficina utilizan instalaciones eléctricas trifásicas, ya que requieren soportar la carga de equipos industriales como calderas, aire acondicionado, un sistema de lavandería, además del sistema de iluminación, el cual funciona con luces LED. También cuentan con un grupo electrógeno como respaldo para asegurar el funcionamiento continuo.

Respecto a las fallas eléctricas, señaló que no son frecuentes, pero sí preocupantes, ya que pueden afectar gravemente la operación diaria. Las más comunes incluyen cortes imprevistos, fallos en el tablero de distribución y problemas con los sistemas de climatización. En cuanto al mantenimiento eléctrico, comentó que suelen delegarlo a técnicos externos de confianza. Sin embargo, a veces enfrentan demoras o falta de disponibilidad inmediata, lo que genera complicaciones operativas.

Sobre el impacto de estas fallas en la productividad, Brian fue claro al decir que puede ser muy alto, ya que una interrupción puede dejar habitaciones sin energía y afectar la atención al cliente. A la hora de contratar un proveedor eléctrico, considera esencial revisar la experiencia comprobada, las certificaciones, la capacidad de respuesta las 24 horas, el cumplimiento de normas y un historial confiable con otros clientes. Aunque también buscan precios competitivos, nunca sacrifican la calidad del servicio.

Relató una mala experiencia pasada con un técnico no certificado que ofrecía rapidez, pero cuyo trabajo resultó poco duradero. Esta situación le enseñó que es mejor invertir en profesionales calificados, incluso si son más costosos, para evitar riesgos innecesarios. También destacó que para él es fundamental que los proveedores cumplan con normativas legales y ofrezcan garantía, ya que esto no solo asegura un trabajo bien hecho, sino que también protege legalmente al negocio y cumple con estándares de seguridad ante el público.

Brian expresó su interés en una plataforma que conecte directamente con proveedores certificados, ya que esto le ahorraría tiempo y facilitaría encontrar opciones confiables sin recurrir a métodos tradicionales. En cuanto a las funcionalidades deseadas en dicha plataforma, mencionó la posibilidad de filtrar por tipo de servicio, nivel de urgencia y ubicación del negocio.

Considera que una herramienta de este tipo podría ofrecerle una ventaja competitiva, ya que permitiría resolver problemas eléctricos con rapidez, mejorar la experiencia del cliente y reducir costos operativos. Cuando necesita encontrar componentes eléctricos específicos, suele comunicarse con proveedores conocidos, buscar en Google o WhatsApp, e incluso acudir a ferreterías especializadas, aunque este proceso suele tomar mucho tiempo.

---

### Segmento #3: Proveedores de componentes o servicios eléctricos certificados

**Entrevista: Juan Lucas**  
- **Sexo:** Masculino  
- **Edad:** 25  
- **Link:** https://youtu.be/I_ISRdC6mHI
- **Inicia en:** 0:01  
- **Duración:** 4:52  
<img src="https://i.postimg.cc/JnyQf1Wb/Screenshot-2025-07-08-at-5-54-27-PM.png">
**Resumen:**  
Juan tiene conocimientos en electricidad y electrónica, y suele encargarse de resolver cualquier problema eléctrico en casa. Si no puede solucionarlo, contacta a amigos electricistas de confianza. Toma medidas preventivas básicas como apagar luces o usar llaves térmicas para evitar sobrecargas.

Nunca ha contratado servicios eléctricos, pero comprende la importancia de cumplir con normas legales debido al riesgo que conlleva el mal manejo eléctrico. Muestra interés en una aplicación como **ElectroLink**, ya que le permitiría acceder fácilmente a proveedores confiables para consultas o necesidades que escapen a sus conocimientos.

### 2.2.3. Análisis de entrevistas

### Segmento #1: Propietarios de hogares urbanos

Los propietarios entrevistados, como **Mari Vallejos**, expresaron una fuerte dependencia de **redes sociales** y **recomendaciones informales** para resolver problemas eléctricos. El **desconocimiento técnico genera ansiedad**, y las decisiones de contratación se basan en criterios como **puntualidad, rapidez, compromiso** y **precio razonable**. La **prevención eléctrica es poco frecuente**, debido a la falta de información o cultura preventiva. Existe una clara **disposición a usar plataformas digitales**, siempre que incluyan **reseñas verificadas, técnicos certificados** y opciones de **filtrado según sus necesidades** (experiencia, precio, horarios).

> **Insight clave:** Este grupo valora la confianza, accesibilidad y la sensación de seguridad que brinda un servicio verificado. Una plataforma como **ElectroLink** puede convertirse en su aliado principal para enfrentar problemas eléctricos con mayor tranquilidad.

---

### Segmento #2: Dueños de PYMES u oficinas

Entrevistados como **Piero Tenorio** y **Brian Cerna** revelan que las fallas eléctricas, aunque no constantes, **generan pérdidas inmediatas** en productividad y atención al cliente. La gestión del mantenimiento suele ser **reactiva y poco sistematizada**. Se reconoce el valor de contratar **técnicos con certificación**, y se busca garantizar **respaldo legal, eficiencia y rapidez**. Este segmento está interesado en **plataformas que ayuden a optimizar el tiempo**, ofrecer control del consumo, mantenimiento preventivo y gestión multi-sucursal. Además, ven **una ventaja competitiva** en automatizar y digitalizar este proceso.

> **Insight clave:** Existe una necesidad de digitalización en la gestión eléctrica empresarial. **ElectroLink** podría ofrecer valor inmediato con funcionalidades como historial de mantenimientos, seguimiento de consumos y contratación de técnicos certificados bajo SLA.

---

### Segmento #3: Proveedores de componentes o servicios eléctricos certificados

Proveedores como **Juan Lucas** valoran el **reconocimiento profesional**, pero enfrentan dificultades para competir con técnicos informales. Mencionan barreras como la **falta de canales para mostrar su experiencia, reseñas o certificaciones**. También existe interés en contar con una plataforma que les **brinde visibilidad, credibilidad** y **facilite la gestión de pedidos**. Están dispuestos a **pagar una suscripción si eso les garantiza mayor alcance**, clientes recurrentes y reputación digital consolidada.

> **Insight clave:** **ElectroLink** puede convertirse en un ecosistema donde los proveedores formales fortalezcan su presencia, profesionalicen su oferta y generen relaciones duraderas con clientes que valoran la calidad y el cumplimiento normativo.


## Análisis de Hallazgos

<img src="https://i.postimg.cc/NFmk0pFF/Screenshot-2025-07-08-at-5-55-09-PM.png"/>

Los entrevistados resaltan como uno de los principales puntos de fricción la dificultad para identificar proveedores eléctricos realmente confiables. La presencia de técnicos informales sin certificaciones claras genera desconfianza. Este hallazgo valida la necesidad de que ElectroLink destaque las certificaciones legales de los proveedores como un diferenciador clave dentro de la plataforma.

<img src="https://i.postimg.cc/SNLGFTHt/Screenshot-2025-07-08-at-5-55-47-PM.png"/>

La posibilidad de llevar un registro digital de los servicios eléctricos realizados (por ejemplo, mantenimientos o reparaciones) es vista como una funcionalidad útil, especialmente para usuarios que hoy lo hacen de forma manual. Esto refuerza la importancia de integrar funciones de gestión documental dentro de ElectroLink, facilitando el seguimiento y la trazabilidad de los trabajos realizados.

<img src="https://i.postimg.cc/4xBbnKf6/Screenshot-2025-07-08-at-5-56-16-PM.png"/>
 
Consultas relacionadas con la recepción de recordatorios permiten identificar una oportunidad para fomentar el mantenimiento eléctrico preventivo. La mayoría de los usuarios no tiene hábitos estructurados en este aspecto. Una funcionalidad de alertas o notificaciones podría ser clave para ayudar a prevenir fallas eléctricas y extender la vida útil de las instalaciones.

<img src="https://i.postimg.cc/wBrXcSs3/Screenshot-2025-07-08-at-5-56-48-PM.png "/>

Tanto en el entorno doméstico como empresarial, los entrevistados valoran la transparencia. Acceder a opiniones reales de otros usuarios es considerado un elemento crucial para decidir a qué proveedor contratar. Por ello, se valida la necesidad de incluir una sección de **comentarios y calificaciones** dentro de la app para fomentar la confianza y facilitar la toma de decisiones.

<img src="https://i.postimg.cc/d32GF3NT/Screenshot-2025-07-08-at-5-57-26-PM.png"/>

Explorar si los usuarios estarían dispuestos a pagar por servicios premium (como soporte prioritario o asesoría técnica especializada) permite analizar la viabilidad de modelos de negocio basados en **suscripciones** o **comisiones por servicio**. Algunos entrevistados afirmaron estar dispuestos a pagar si los beneficios ofrecidos son claros y valiosos, lo cual abre la puerta a monetización sostenible para ElectroLink.

<br> 

## 2.3. Needfinding

El needfinding es una metodología de diseño e innovación que consiste en descubrir las necesidades reales de los usuarios a través de la investigación cualitativa, la observación y las entrevistas, con el fin de generar soluciones relevantes y exitosas, en lugar de basarse en suposiciones previas. 
En esta sección, el equipo presenta los elementos del Needfinding.

### 2.3.1. User Personas

En esta sección, el equipo presenta a los user personas de acuerdo a los segmenots objetivos

**Segmento #1**
<img src="https://i.postimg.cc/wjYCqGfK/Olivia-P-rez-4.png"/>

**Segmento #2**
<img src="https://i.postimg.cc/L5ZWRtj6/Eduardo-Gonzales.png"/>

**Segmento #3**
<img src="https://i.postimg.cc/85Tk7CZS/Alejandro-L-pez-9.png"/>

### 2.3.2. User Task Matrix

En esta sección se detallan las tareas que realizan los diferentes segmentos de usuarios representados por los User Personas de **ElectroLink**, con el objetivo de cumplir sus metas relacionadas con el mantenimiento preventivo de sistemas eléctricos en hogares, oficinas o como parte de su actividad profesional.

---

### Olivia Pérez – Propietaria de hogar urbano

| Actividades                                          | Frecuencia     | Importancia |
|------------------------------------------------------|----------------|-------------|
| Buscar electricistas certificados                    | Frecuentemente | Alta        |
| Agendar mantenimientos preventivos para el hogar     | Ocasionalmente | Alta        |
| Comparar calificaciones de proveedores               | Frecuentemente | Media       |
| Buscar soluciones que ahorren energía en el hogar    | Ocasionalmente | Media       |
| Pedir recomendaciones a vecinos o conocidos          | Rara vez       | Media       |

---

### Eduardo Gonzales – Dueño de PYME / Oficina

| Actividades                                          | Frecuencia     | Importancia |
|------------------------------------------------------|----------------|-------------|
| Buscar formas de reducir costos energéticos          | Frecuentemente | Alta        |
| Contratar servicios de mantenimiento eléctrico        | Ocasionalmente | Alta        |
| Llevar registro del historial de mantenimiento        | Ocasionalmente | Media       |
| Buscar proveedores o técnicos de confianza            | Ocasionalmente | Alta        |
| Usar herramientas digitales para gestionar instalaciones | A veces     | Media       |

---

### Alejandro López – Proveedor de servicios eléctricos certificados

| Actividades                                          | Frecuencia     | Importancia |
|------------------------------------------------------|----------------|-------------|
| Buscar nuevos clientes o trabajos                    | Frecuentemente | Alta        |
| Actualizar su disponibilidad de servicios en plataformas | Ocasionalmente | Media    |
| Gestionar pedidos y comunicación con clientes        | Frecuentemente | Alta        |
| Pedir reseñas o testimonios a sus clientes           | Rara vez       | Media       |
| Mantenerse al día con normativas eléctricas          | Ocasionalmente | Alta        |

<hr>

### 2.3.3. User Journey Mapping

Un journey map es una representación visual que detalla las acciones, pensamientos y emociones de una persona (cliente o usuario) a medida que interactúa con una empresa, producto o servicio para alcanzar un objetivo. En esta seccion presentaremos el Journey Map de nuestro proyecto.

<img src="https://i.postimg.cc/SxDbgGrw/xcvcvc.png"/>

<hr>


#### 2.3.4. Empathy Mapping

Un mapa de empatía es una herramienta visual y colaborativa que permite a los equipos entender profundamente a un usuario, capturando sus pensamientos, sentimientos, percepciones y comportamientos en relación con un producto o servicio. En esta sección, el equipo presenta el empathy mapping para cada user persona.

<hr>

<img src="https://i.postimg.cc/xdzgXfct/ffsd.png"/>

**Olivia Rodriguez**

<hr>

<img src="https://i.postimg.cc/pL9JSWYR/fsdfsdfsd.png"/>

**Eduardo Gonzales**

<hr>


<img src="https://i.postimg.cc/59n5NYsf/Captura.png"/>

**Alejandro Lopez**

<hr>


### 2.3.5. As-is Scenario Mapping

Un "As Is Scenario Map" es una herramienta de diseño de experiencias de usuario (UX) que documenta el estado actual y el recorrido de un usuario al interactuar con un producto o servicio, incluyendo sus acciones, pensamientos y emociones en cada paso. En esta sección, el equipo presenta los escnerarios as is para sus respectivos users personas

**Alejandro Lopez**
<img src="https://i.postimg.cc/cLN7xCsY/imagen-2025-07-08-205115361.png"/>

**Áreas Negativas** 

Promoción de productos:
- Frustración por la baja efectividad de la publicidad.
- Sentimiento de que no alcanza a los clientes correctos.
- Alto gasto en publicidad sin retorno claro.
  
Atención de consultas:
- Agobio y ansiedad por la sobrecarga.
- Dudas sobre su profesionalismo.
- Falta de tiempo para responder con calidad.
  
Cotizaciones:
- Estrés por cálculos manuales.
- Ineficiencia y desorganización.
- Percepción de poca escalabilidad y falta de optimización.
  
Entrega de productos:
- Preocupación por los errores.
- Falta de digitalización.
- Sensación de sistema poco confiable y propenso a reclamos.

**Áreas Positivas**

Promoción de productos:
- Esperanza cuando recibe contacto de un nuevo cliente.
  
Atención de consultas:
- No se identifican ups, lo que revela una necesidad urgente de mejora.

Cotizaciones:
- Alivio al concretar una venta sin errores, aunque depende de factores externos.
  
Entrega de productos:
- Satisfacción al cerrar una venta sin errores.
- Tranquilidad una vez que el cliente confirma.
  
**Conclusión**

Alejandro enfrenta varios puntos críticos en su proceso: publicidad poco efectiva, consultas y cotizaciones manuales que lo agobian, y entregas propensas a errores. Aunque hay momentos de esperanza, su experiencia general es frustrante. Esto evidencia la necesidad urgente de herramientas digitales que lo ayuden a automatizar, organizar y profesionalizar su servicio.

**Eduardo Gonzales**

<img src="https://i.postimg.cc/LXZJML0j/imagen-2025-07-08-205223250.png"/>

**Áreas negativas**

Identificar una necesidad operativa o de mantenimiento:
- Eduardo parte con incertidumbre al preguntarse si debe resolver el problema de inmediato o si puede esperar, lo que genera estrés.
- Se siente preocupado y frustrado porque los problemas son frecuentes y no siempre encuentra soluciones rápidas, lo que podría acarrear riesgos operativos o pérdidas importantes para la empresa.

Buscar proveedores adecuados:
- Esta etapa está llena de desconfianza. Eduardo duda si los proveedores entienden realmente lo que necesita o si solo quieren cerrar una venta rápida.
- Se siente inseguro e impaciente ante las respuestas lentas y poco claras, lo que afecta su percepción de profesionalismo y genera tensión en un momento clave para la toma de decisiones.
  
Solicitar cotización y evaluar propuestas:
- Eduardo se enfrenta a la ansiedad de cometer errores al seleccionar proveedores, y sufre por tener que repetir procesos que no mejoran con el tiempo.
- La sobrecarga de evaluar múltiples propuestas, sin estar seguro de si le responderán bien tras la compra, lo hace sentirse cansado, inseguro y con miedo a consecuencias graves.
  
Supervisar ejecución y validar resultados:
- Aunque ya en una etapa avanzada, Eduardo aún siente incertidumbre y dudas sobre si tomó la mejor decisión o si dejó pasar una opción superior.
- Esto lo hace sentirse dudoso, y aunque confía en algunos proveedores, no siempre puede validar si son la mejor opción a largo plazo.

**Áreas positivas**

Identificar una necesidad operativa o de mantenimiento:

- Eduardo demuestra proactividad al realizar inspecciones periódicas y tomar nota del estado de los equipos, lo que le da visibilidad y control sobre su entorno operativo.
- Se siente comprometido con su equipo y con la empresa, lo que impulsa su deseo de mejorar continuamente.
  
Buscar proveedores adecuados:
- Aunque tiene dudas, Eduardo explora múltiples canales (web, catálogos, redes, recomendaciones) para encontrar proveedores, lo que muestra una búsqueda activa y estratégica.
- Tiene un enfoque exigente y selectivo, no se conforma con la primera opción, lo que garantiza estándares de calidad más altos.

Solicitar cotización y evaluar propuestas:
- Filtra activamente a proveedores que no cumplen con aspectos técnicos o de confianza, lo que indica una evaluación rigurosa.
- Esta etapa, aunque estresante, muestra que Eduardo sabe qué quiere y no acepta cualquier solución, buscando equilibrio entre precio, calidad y conocimiento técnico.

Supervisar ejecución y validar resultados:
- Finalmente, cuando logra decidir con seguridad, se siente aliviado por haber elegido correctamente pensando en el largo plazo.
- Esta satisfacción final indica que, a pesar del proceso complejo, Eduardo valora las decisiones bien fundamentadas y aspira a establecer relaciones sostenibles con los proveedores.

**Conclusión**

Eduardo es un perfil técnico y exigente, que valora la calidad, la previsión y la confiabilidad en todo el proceso de adquisición y mantenimiento. Aunque su recorrido está lleno de tensiones y dudas, especialmente en la interacción con proveedores, también muestra una actitud proactiva y profesional. Una plataforma que le brinde confianza, claridad, rapidez en respuestas y herramientas para comparar y validar proveedores fácilmente puede ayudarlo a reducir su ansiedad, optimizar decisiones y reforzar la seguridad en sus elecciones.

**Olivia Rodriguez**

<img src="https://i.postimg.cc/gJR27dnD/imagen-2025-07-08-205305571.png"/>

**Áreas negativas**

Buscar proveedores confiables:
- Olivia se enfrenta a una búsqueda larga, tediosa y desconfiada, lo que le genera cansancio y frustración.
- No puede confiar en cualquier empresa, y siente que el proceso es muy desgastante, además de que nada le garantiza la calidad de los materiales.
  
Contactar y validar a los proveedores:
- Se siente insegura sobre permitir el ingreso a su casa y teme contactar a proveedores sin garantías, lo que le genera nerviosismo y desconfianza.
- Olivia percibe que hacer un proceso de descarte por su cuenta es ineficiente, lo que la hace sentir molesta cuando los proveedores son informales o poco claros.

Solicitar cotizaciones y comparar:
- Se ve obligada a comparar manualmente propuestas en hojas de cálculo, recibiendo cotizaciones en formatos poco intuitivos, lo que la abruma.
- Siente que los precios no siempre son justos y se cansa de descartar opciones sin apoyo externo.

Tomar la decisión y agendar el servicio:
- Aun en la fase final, Olivia no siempre confía en la calidad de lo que va a recibir, ni en la relación entre el costo y el producto final.
- Se siente inquieta, nerviosa y exhausta, especialmente si no tiene claridad sobre las garantías o si invirtió mucho tiempo en el proceso sin estar completamente segura.

**Áreas positivas**

Buscar proveedores confiables:
- Olivia es proactiva, utiliza Google, páginas web y preguntas a familiares o amigos de confianza.
- Guarda enlaces y captura información útil, y valora la idea de una plataforma donde todo ya esté validado, lo que indica apertura a soluciones digitales confiables.

Contactar y validar a los proveedores:
- Pide certificados, RUC o documentos de formalidad, mostrando una actitud responsable y detallista en su proceso de selección.
- Aunque frustrada, busca garantías y seguridad, lo que refuerza su interés por soluciones formales y transparentes.

Solicitar cotizaciones y comparar:
- A pesar del cansancio, Olivia desea prevenir problemas a futuro, lo que muestra un enfoque de largo plazo.
- Expresa que le gustaría tener una plataforma que la ayude a comparar todo más fácilmente, lo que es una oportunidad clara para digitalizar y simplificar su experiencia.

Tomar la decisión y agendar el servicio:
- Olivia valida documentos y garantías antes de cerrar un acuerdo, lo que muestra que se preocupa por protegerse.
- Quiere asegurarse de que su elección evite problemas futuros, lo que revela una clara orientación hacia la prevención.

**Conclusión**

Olivia es una usuaria cautelosa, exigente y preocupada por la seguridad y la calidad, pero actualmente enfrenta un proceso cargado de incertidumbre, informalidad y desorganización. Su experiencia se ve afectada por la falta de herramientas que la acompañen en todo el recorrido. Una plataforma que le brinde proveedores verificados, cotizaciones estandarizadas, comparaciones automáticas y validaciones de calidad y seguridad tendría un impacto muy positivo, reduciendo su ansiedad, optimizando su tiempo y fortaleciendo su confianza al momento de tomar decisiones.

## 2.4. Ubiquitous Language

El Lenguaje Ubicuo es un vocabulario común y riguroso que un equipo de desarrollo de software y los expertos del negocio comparten y utilizan de manera consistente en todas las comunicaciones, el código y la documentación para evitar ambigüedades y malentendidos. En esta sección, el equipo presenta el lenguaje Ubicuo.

**Glosario del Dominio del Negocio - ElectroLink**

Este glosario contiene términos clave relacionados al dominio del proyecto ElectroLink. Cada término está en inglés, seguido de su equivalente en español entre paréntesis. Las definiciones están redactadas en español de forma clara y sin ambigüedades, para facilitar la comunicación entre todos los miembros del equipo y stakeholders.

**1.  Stakeholders & Roles**

* **Homeowner** (Propietario de vivienda)
    * Persona que reside en un hogar y busca soluciones eléctricas confiables y certificadas para prevenir o resolver fallos.

* **Business Owner** (Dueño de empresa)
    * Responsable de una oficina o PYME que necesita mantener el sistema eléctrico eficiente, operativo y dentro del marco legal.

* **Service Provider** (Proveedor de servicios)
    * Técnico profesional con certificación que ofrece servicios de instalación, reparación o mantenimiento eléctrico.

* **Component Supplier** (Proveedor de componentes)
    * Empresa o persona encargada de la venta de dispositivos, piezas o insumos eléctricos certificados.

* **Platform Administrator** (Administrador de plataforma)
    * Miembro del equipo responsable de validar, gestionar y supervisar las actividades y registros dentro de ElectroLink.


**2. Servicios y Mantenimiento**

* **Preventive Maintenance** (Mantenimiento preventivo)
    * Servicio programado que permite identificar y corregir posibles fallas eléctricas antes de que ocurran.

* **Emergency Service** (Servicio de emergencia)
    * Atención inmediata para resolver fallos eléctricos inesperados que comprometen la seguridad o funcionalidad.

* **Electric Assessment** (Evaluación eléctrica)
    * Diagnóstico que realiza un proveedor para determinar el estado de una instalación eléctrica.

* **Installation Service** (Servicio de instalación)
    * Proceso de conexión o implementación de componentes eléctricos en viviendas o negocios, cumpliendo estándares técnicos.

* **Electrical Upgrade** (Actualización eléctrica)
    * Mejora o sustitución de partes de una instalación para adaptarla a nuevas necesidades o normas de seguridad.


**3. Funcionalidades de la Plataforma**

* **Service Request** (Solicitud de servicio)
    * Acción del usuario para iniciar una contratación de servicios desde la plataforma.

* **Matchmaking** (Emparejamiento)
    * Proceso automatizado para conectar a un usuario con el proveedor más adecuado según filtros como ubicación, calificación y disponibilidad.

* **Real-Time Tracking** (Seguimiento en tiempo real)
    * Visualización del estado y avance de un servicio solicitado a través de la plataforma.

* **Verified Profile** (Perfil verificado)
    * Estado de un proveedor que ha sido validado por la plataforma mediante documentación y procesos de control.

* **Rating and Review** (Calificación y reseña)
    * Sistema de puntuación y comentarios que permite evaluar la experiencia del usuario con un proveedor.

* **Subscription Plan** (Plan de suscripción)
    * Modalidad de pago por parte del proveedor para acceder a beneficios dentro de la plataforma (visibilidad, herramientas, clientes).

* **Booking History** (Historial de contrataciones)
    * Registro de todos los servicios contratados, realizados y evaluados por un usuario o proveedor.


**4. Seguridad y Cumplimiento**

* **Certified Technician** (Técnico certificado)
    * Profesional acreditado por una entidad oficial para realizar trabajos eléctricos conforme a la ley.

* **Legal Compliance** (Cumplimiento legal)
    * Condición de operar dentro de los estándares establecidos por entidades regulatorias del sector eléctrico.

* **Risk Prevention** (Prevención de riesgos)
    * Estrategia para evitar accidentes, daños o fallos eléctricos mediante prácticas seguras y mantenimiento adecuado.

* **Safety Assurance** (Garantía de seguridad)
    * Compromiso de que los servicios ofrecidos cumplen con medidas de protección para personas, instalaciones y equipos.


**5. Otros conceptos del dominio**

* **Electric Incident** (Incidente eléctrico)
    * Evento disruptivo como sobrecarga, cortocircuito o fallo en la instalación que requiere intervención técnica.

* **Energy Optimization** (Optimización energética)
    * Prácticas que buscan mejorar el uso de energía eléctrica, reduciendo costos y desperdicios.

* **Informal Market** (Mercado informal)
    * Entorno de prestación de servicios sin regulación, licencias ni garantías de seguridad.

* **Digital Presence** (Presencia digital)
    * Visibilidad que tiene un proveedor dentro de la plataforma, influyendo en su reputación y oportunidades de negocio.

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

En este apartado se formalizan los requerimientos del sistema en formato estructurado y verificable. Se presenta el catálogo de requisitos, modelos de casos de uso, restricciones técnicas y condiciones de aceptación. Esta especificación servirá como base contractual entre el equipo de desarrollo y los interesados.

## 3.1. To-Be Scenario Mapping

En esta sección, el equipo presenta el to be scenario mapping para sus users personas en realción a los semgnetos objetivos

Semgmento 1
<img src="https://i.postimg.cc/QxR9064h/imagen-2025-07-08-205917558.png"/>

Segmento 2
<img src="https://i.postimg.cc/wjZt4ww9/imagen-2025-07-08-205645366.png"/>

Segmento 3
<img src="https://i.postimg.cc/J00MLLhv/imagen-2025-07-08-205729249.png"/>

## 3.2. User Stories
En esta sección, se definieron las epicas y la visualización de las user stories con sus respectivos criterios de aceptación.

<hr>

# Epics

<table border="1">
<tr>
    <th>EpicId</th>
    <th>Título</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>EP-01</td>
    <td>Gestión de Acceso de Usuarios</td>
    <td>Como usuario, quiero un sistema completo de acceso para registrarme, autenticarme y gestionar mis credenciales de manera segura según mi perfil específico.</td>
  </tr>
  <tr>
    <td>EP-02</td>
    <td>Experiencia de Usuario en Procesos de Autenticación</td>
    <td>Como usuario, quiero tener una experiencia clara y asistida durante los procesos de registro y autenticación para completarlos con éxito y sin frustraciones.</td>
  </tr>
  <tr>
    <td>EP-03</td>
    <td>Personalización y Seguridad de la Cuenta</td>
    <td>Como usuario, quiero tener control sobre la seguridad y la configuración de mi cuenta para proteger mi información y adaptarla a mis necesidades específicas.</td>
  </tr>
  <tr>
    <td>EP-04</td>
    <td>Contratación y Seguimiento de Servicios Eléctricos</td>
    <td>Como propietario o PYME, quiero contratar servicios paso a paso y darles seguimiento, para resolver mis problemas eléctricos de manera estructurada y segura.</td>
  </tr>
  <tr>
    <td>EP-05</td>
    <td>Programación y Gestión de Servicios Preventivos</td>
    <td>Como propietario o PYME, quiero programar mantenimientos preventivos y revisar mi historial de servicios, para garantizar un sistema eléctrico seguro y funcional.</td>
  </tr>
  <tr>
    <td>EP-06</td>
    <td>Gestión Operativa de los Proveedores</td>
    <td>Como proveedor, quiero administrar mi agenda, servicios y pagos, para tener control sobre mis operaciones y oportunidades de negocio.</td>
  </tr>
  <tr>
    <td>EP-07</td>
    <td>Funcionalidades de Confianza y Transparencia en el Ecosistema</td>
    <td>Como usuario, quiero interactuar con un entorno confiable, transparente y claro, para sentirme seguro al contratar servicios, comparar opciones y tomar decisiones informadas.</td>
  </tr>
  <tr>
    <td>EP-08</td>
    <td>Navegación en la Landing Page</td>
    <td>Como visitante, quiero navegar en una Landing page que me brinde información necesaria para tomar una decisión informada.</td>
  </tr>
  <tr>
    <td>EP-09</td>
    <td>Gestión de Suscripciones y Pagos (Proveedores)</td>
    <td>Como proveedor, quiero gestionar mis planes de suscripción, procesar pagos de forma segura y acceder a mi historial de facturación, para mantener mi cuenta activa y funcional.</td>
  </tr>
  <tr>
    <td>EP-10</td>
    <td>Gestión de Activos y Recursos</td>
    <td>Como usuario (propietario o proveedor), quiero registrar y gestionar mis activos relevantes (propiedades, inventario de componentes) para facilitar la operativa del sistema.</td>
  </tr>
  <tr>
    <td>EP-11</td>
    <td>Gestión de Servicios Ofrecidos</td>
    <td>Como técnico, quiero gestionar mi catálogo de servicios ofrecidos, para mantenerlo actualizado y mostrar claramente a los clientes mi oferta y especialidades.</td>
  </tr>
  <tr>
    <td>EP-12</td>
    <td>Gestión de Propiedades</td>
    <td>Como desarrollador, quiero implementar endpoints para registrar, consultar y administrar propiedades de los propietarios, para permitir la selección de ubicación durante la solicitud.</td>
  </tr>
  <tr>
    <td>EP-13</td>
    <td>Gestión de Componentes Técnicos</td>
    <td>Como desarrollador, quiero crear endpoints CRUD para administrar el inventario de componentes eléctricos de los técnicos, para garantizar el stock durante la asignación de servicios.</td>
  </tr>
  <tr>
    <td>EP-14</td>
    <td>Asistente de Solicitud de Servicio</td>
    <td>Como desarrollador, quiero implementar la lógica escalonada del flujo de solicitud del propietario, para validar planes, verificar límites y facilitar la selección guiada.</td>
  </tr>
  <tr>
    <td>EP-15</td>
    <td>Evaluación de Servicios Completados</td>
    <td>Como desarrollador, quiero permitir que los usuarios dejen evaluaciones tras completar un servicio, para alimentar las métricas del sistema y mejorar la calidad del servicio.</td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-01</td>
    <td>visitante de la landing page</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de Características y Beneficios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante de la landing page</b>, quiero <b>ver claramente las características y beneficios de la plataforma</b>, para así <b>entender cómo puede ayudarme y decidir si registrarme</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización de beneficios para usuarios</b><br>
          Dado que un visitante se encuentra explorando la plataforma informativa<br>
          Cuando revisa la sección de propuestas de valor<br>
          Entonces debe identificar claramente los beneficios específicos para Propietarios y Técnicos<br>
          Y cada beneficio debe tener una descripción breve y clara.
        </li>
        <li><b>Escenario #2: Visualización de características principales</b><br>
          Dado que un visitante se encuentra en la plataforma informativa<br>
          Cuando explora la sección de características<br>
          Entonces debe ver las funcionalidades destacadas de la plataforma<br>
          Y cada característica debe tener un título descriptivo y una explicación concisa de su funcionamiento.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-02</td>
    <td>visitante indeciso sobre la plataforma</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de Testimonios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante indeciso sobre la plataforma</b>, quiero <b>ver testimonios de usuarios reales</b>, para así <b>aumentar mi confianza en el servicio antes de registrarse</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización de testimonios diversos</b><br>
          Dado que el visitante explora la plataforma informativa<br>
          Cuando accede a la sección de testimonios<br>
          Entonces debe ver al menos 3 testimonios diferentes<br>
          Y cada testimonio debe mostrar: Nombre de usuario, tipo de usuario (Propietario/Técnico), calificación y comentario<br>
          Y las calificaciones deben ser visualmente claras.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-03</td>
    <td>visitante que accede desde diferentes dispositivos</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Adaptabilidad a Diferentes Dispositivos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante que accede desde diferentes dispositivos</b>, quiero <b>que la landing page se adapte correctamente a mi pantalla</b>, para así <b>tener una experiencia óptima independientemente del dispositivo que use</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Experiencia en dispositivo móvil</b><br>
          Dado que un visitante accede a la plataforma informativa desde un dispositivo móvil<br>
          Cuando la información es presentada<br>
          Entonces todos los elementos se reorganizan para adaptarse a una pantalla vertical<br>
          Y no requiere desplazamiento horizontal<br>
          Y todos los textos son legibles sin necesidad de ampliar la vista.
        </li>
        <li><b>Escenario #2: Experiencia en tableta o escritorio</b><br>
          Dado que un visitante accede a la plataforma informativa desde una tableta o un ordenador<br>
          Cuando la información es presentada<br>
          Entonces el diseño aprovecha el espacio horizontal adicional<br>
          Y mantiene una experiencia de navegación fluida y atractiva.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-04</td>
    <td>visitante de la página</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de una Sección Principal</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante de la página</b>, quiero <b>ver una sección principal atractiva que me presente un breve resumen de la idea del producto</b>, para así <b>entender rápidamente de qué se trata el servicio</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Presentación del propósito de la plataforma</b><br>
          Dado que un visitante accede a la plataforma informativa<br>
          Cuando la carga inicial se completa<br>
          Entonces se muestra una sección principal con un título que explica el propósito del sistema<br>
          Y se incluye un subtítulo que resume el valor principal del servicio<br>
          Y se presenta una llamada a la acción principal para invitar al registro.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-05</td>
    <td>visitante</td>
    <td>Alta</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Navegación sin errores</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante</b>, quiero <b>navegar por la página web sin encontrar errores</b>, para así <b>tener una experiencia fluida que me anime a registrarme</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Carga completa de la plataforma</b><br>
          Dado que un visitante accede a la plataforma informativa<br>
          Cuando la carga de la página se completa<br>
          Entonces todos los elementos visuales e informativos se muestran correctamente<br>
          Y no existen enlaces que dirijan a destinos incorrectos o inexistentes.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-06</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Navegación mediante Encabezado</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero un <b>menú de navegación claro en el encabezado</b>, para así <b>acceder fácilmente a las diferentes secciones de la página</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Acceso a secciones desde el encabezado</b><br>
          Dado que que un visitante explora la plataforma informativa<br>
          Cuando utiliza las opciones de navegación en el encabezado<br>
          Entonces puede desplazarse a las diferentes secciones informativas<br>
          Y el encabezado permanece accesible durante el desplazamiento.
        </li>
        <li><b>Escenario #2: Navegación en dispositivos de pantalla pequeña</b><br>
          Dado que que un visitante accede desde un dispositivo móvil<br>
          Cuando interactúa con la opción de menú principal<br>
          Entonces se despliegan las opciones de navegación a las distintas secciones.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-07</td>
    <td>visitante</td>
    <td>Baja</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización del Pie de página</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante</b>, quiero <b>ver un pie de página organizado con accesos directos e información de contacto</b>, para así <b>encontrar información adicional rápidamente</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Contenido completo del pie de página</b><br>
          Dado que que un visitante se desplaza hasta el final de la plataforma informativa<br>
          Cuando llega al pie de página<br>
          Entonces debe ver una sección con enlaces a Términos y Condiciones y Política de Privacidad<br>
          Y debe encontrar información de contacto<br>
          Y enlaces a las redes sociales de la empresa.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-08</td>
    <td>potencial cliente</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Ver Información del Startup</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>potencial cliente</b>, quiero <b>conocer información sobre la empresa desarrolladora</b>, para así <b>evaluar su credibilidad y confiabilidad</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Acceso a información corporativa</b><br>
          Dado que que un visitante navega por la plataforma informativa<br>
          Cuando se desplaza a la sección sobre la empresa<br>
          Entonces debe encontrar información clara sobre la startup y el equipo fundador<br>
          Y la información debe transmitir profesionalidad y confianza.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-09</td>
    <td>visitante interesado</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Conocer la Misión de la Startup</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante interesado</b>, quiero <b>conocer la misión de la empresa</b>, para así <b>entender sus valores y propósito</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visibilidad de la declaración de misión</b><br>
          Dado que que un visitante navega por la sección sobre la empresa<br>
          Cuando busca información sobre los propósitos de la empresa<br>
          Entonces debe encontrar claramente destacada la declaración de misión<br>
          Y esta debe estar redactada de forma concisa y comprensible.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-10</td>
    <td>visitante interesado</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Conocer la Visión de la Startup</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante interesado</b>, quiero <b>conocer la visión de la empresa</b>, para así <b>entender sus objetivos a largo plazo y su proyección de futuro</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visibilidad de la declaración de visión</b><br>
          Dado que que un visitante navega por la sección sobre la empresa<br>
          Cuando busca información sobre las metas futuras de la empresa<br>
          Entonces debe encontrar claramente destacada la declaración de visión<br>
          Y esta debe estar redactada de forma inspiradora y orientada al futuro.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-11</td>
    <td>visitante interesado</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Conocer más a fondo los servicios que ofrecen</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante interesado</b>, quiero <b>conocer de manera más específica los servicios que ofrecen por medio de capturas de pantallas</b>, para así <b>comprender su solución y decidir si optar por ella</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización de la solución en acción</b><br>
          Dado que que un visitante se encuentra en la sección de características o servicios<br>
          Cuando explora cómo funciona la plataforma<br>
          Entonces visualiza representaciones gráficas o capturas de pantalla de la aplicación<br>
          Y estas imágenes ilustran las funcionalidades clave del sistema.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-12</td>
    <td>visitante interesado</td>
    <td>Media</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Ver planes de suscripción disponibles</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>visitante interesado</b>, quiero <b>ver una sección clara que me presente los planes de suscripción disponibles, separados por "Planes para Técnicos" y "Planes para Propietarios"</b>, para así <b>comparar fácilmente sus características y precios</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Comparación de planes para Propietarios</b><br>
          Dado que que un visitante está interesado en los planes para Propietarios<br>
          Cuando accede a la sección de planes<br>
          Entonces visualiza una comparativa entre el plan Básico y el plan Premium<br>
          Y puede identificar claramente los límites y beneficios de cada uno.
        </li>
        <li><b>Escenario #2: Visualización de planes para Técnicos</b><br>
          Dado que que un visitante está interesado en los planes para Técnicos<br>
          Cuando accede a la sección de planes<br>
          Entonces visualiza la oferta de planes de suscripción para su rol<br>
          Y comprende los beneficios asociados a cada nivel.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-13</td>
    <td>dueño de hogar</td>
    <td>Media</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de cuentas como Dueño de Hogar</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>dueño de hogar</b>, quiero <b>registrarme para tener una cuenta en la aplicación</b>, para así <b>gestionar los componentes eléctricos de mi vivienda</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Selección de rol de usuario</b><br>
          Dado que que una persona no registrada accede a la funcionalidad de registro<br>
          Cuando selecciona el rol "Dueño de Hogar"<br>
          Entonces el sistema le presenta los campos requeridos para ese rol.
        </li>
        <li><b>Escenario #2: Registro exitoso con datos válidos</b><br>
          Dado que que un futuro dueño de hogar ha completado todos los campos obligatorios con información válida<br>
          Cuando solicita el registro de su cuenta<br>
          Entonces el sistema crea una cuenta de usuario con el rol "Propietario"<br>
          Y le informa que se ha enviado una comunicación para verificar su cuenta.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-14</td>
    <td>dueño o representante de empresa</td>
    <td>Media</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de cuentas como Dueño de Empresa</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>dueño o representante de empresa</b>, quiero <b>registrarme para tener una cuenta en la aplicación</b>, para así <b>gestionar los componentes eléctricos de mis instalaciones comerciales</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Selección de rol de usuario</b><br>
          Dado que que una persona no registrada accede a la funcionalidad de registro<br>
          Cuando selecciona el rol "Dueño de Empresa"<br>
          Entonces el sistema le presenta los campos requeridos para ese rol, incluyendo el nombre de la empresa.
        </li>
        <li><b>Escenario #2: Registro exitoso con datos válidos</b><br>
          Dado que que un futuro dueño de empresa ha completado todos los campos obligatorios con información válida<br>
          Cuando solicita el registro de su cuenta<br>
          Entonces el sistema crea una cuenta de usuario con el rol "Propietario" de tipo PYME<br>
          Y le informa que se ha enviado una comunicación para verificar su cuenta.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Técnico de componentes eléctricos y/o servicios</td>
    <td>Media</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de cuentas para Técnicos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico de componentes eléctricos y/o servicios</b>, quiero <b>registrarme para tener una cuenta en la aplicación</b>, para así <b>ofrecer mis productos y servicios a los usuarios</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Selección de rol de usuario</b><br>
          Dado que que una persona no registrada accede a la funcionalidad de registro<br>
          Cuando selecciona el rol "Técnico"<br>
          Entonces el sistema le presenta los campos requeridos para el perfil profesional.
        </li>
        <li><b>Escenario #2: Registro exitoso con datos válidos</b><br>
          Dado que que un futuro técnico ha completado todos los campos obligatorios con información válida<br>
          Cuando solicita el registro de su cuenta<br>
          Entonces el sistema crea una cuenta de usuario con el rol "Técnico"<br>
          Y le informa que se ha enviado una comunicación para verificar su cuenta.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-16</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Verificación de cuenta por correo electrónico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>verificar mi cuenta a través de un enlace enviado por correo electrónico</b>, para así <b>confirmar mi identidad</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Envío de comunicación de verificación</b><br>
          Dado que que un usuario se ha registrado exitosamente<br>
          Cuando el proceso de registro finaliza<br>
          Entonces el sistema envía una comunicación electrónica a la dirección proporcionada<br>
          Y la comunicación contiene una instrucción y un medio único para verificar la cuenta.
        </li>
        <li><b>Escenario #2: Verificación exitosa de cuenta</b><br>
          Dado que que un usuario ha recibido la comunicación de verificación<br>
          Cuando utiliza el medio de verificación proporcionado<br>
          Entonces su cuenta es marcada como verificada en el sistema<br>
          Y se le notifica que la verificación fue exitosa.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-17</td>
    <td>usuario registrado</td>
    <td>Baja</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Inicio de sesión de usuarios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario registrado</b>, quiero <b>iniciar sesión en la aplicación con mis credenciales</b>, para así <b>acceder a mi cuenta y utilizar las funcionalidades de la plataforma</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Inicio de sesión exitoso con credenciales válidas</b><br>
          Dado que que un usuario registrado y verificado se encuentra en la funcionalidad de acceso<br>
          Cuando ingresa sus credenciales correctas y solicita el acceso<br>
          Entonces el sistema valida las credenciales<br>
          Y le concede acceso a su panel personalizado según su rol.
        </li>
        <li><b>Escenario #2: Intento de inicio de sesión con credenciales inválidas</b><br>
          Dado que que un usuario se encuentra en la funcionalidad de acceso<br>
          Cuando ingresa un correo electrónico y/o contraseña incorrectos<br>
          Entonces el sistema le niega el acceso<br>
          Y le informa que las credenciales son inválidas.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-18</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Validación de datos de registro</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>recibir retroalimentación inmediata sobre la validez de los datos que ingresó durante el registro</b>, para así <b>corregir errores rápidamente</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Validación de formato de correo electrónico</b><br>
          Dado que que un usuario está completando el formulario de registro<br>
          Cuando ingresa un texto en el campo de correo electrónico que no tiene un formato válido<br>
          Entonces el sistema le informa que el formato del correo no es válido.
        </li>
        <li><b>Escenario #2: Validación de correo electrónico ya registrado</b><br>
          Dado que que un usuario está en el formulario de registro<br>
          Cuando ingresa un correo electrónico que ya está registrado en el sistema<br>
          Entonces el sistema le informa que la dirección de correo ya está en uso.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-19</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Mensajes de éxito retroalimentación de registro</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>recibir mensajes claros y accesibles al completar el registro sobre éxito</b>, para así <b>entender fácilmente el resultado de mis acciones</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Mensaje de éxito al completar el registro</b><br>
          Dado que que el usuario ha completado correctamente el proceso de registro<br>
          Cuando el sistema procesa la solicitud con éxito<br>
          Entonces el sistema muestra un mensaje de confirmación<br>
          Y informa sobre el siguiente paso (verificación de correo).
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-20</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Mensajes de error retroalimentación de registro</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>recibir mensajes claros y accesibles al completar el registro sobre cualquier error a la hora de completar el formulario</b>, para así <b>entender fácilmente el resultado de mis acciones y saber cómo proceder</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Mensaje de error por problemas del sistema</b><br>
          Dado que que el usuario ha solicitado completar su registro<br>
          Cuando ocurre un error del sistema durante el procesamiento<br>
          Entonces el sistema muestra un mensaje de error genérico<br>
          Y informa que puede intentarlo de nuevo<br>
          Y los datos ingresados se conservan para facilitar un nuevo intento.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-21</td>
    <td>usuario registrado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Recuperación de Contraseña</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario registrado</b>, quiero <b>recuperar mi contraseña en caso de olvidarla</b>, para así <b>volver a acceder a mi cuenta de manera segura</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Solicitud de recuperación con correo válido</b><br>
          Dado que que un usuario se encuentra en la página de recuperación de contraseña<br>
          Cuando ingresa el correo electrónico asociado a su cuenta<br>
          Entonces el sistema envía un correo con instrucciones y un enlace único de restablecimiento<br>
          Y muestra un mensaje de confirmación indicando que revise su correo.
        </li>
        <li><b>Escenario #2: Finalización exitosa del restablecimiento</b><br>
          Dado que que un usuario ha seguido el enlace de restablecimiento<br>
          Cuando ingresa y confirma una nueva contraseña que cumple los requisitos de seguridad<br>
          Entonces la contraseña es actualizada en el sistema<br>
          Y recibe un mensaje de confirmación del cambio exitoso.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-22</td>
    <td>usuario autenticado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Cierre de Sesión</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario autenticado</b>, quiero <b>cerrar mi sesión de forma segura</b>, para así <b>proteger mi cuenta cuando termine de usar la aplicación</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Cierre de sesión voluntario</b><br>
          Dado que que un usuario está autenticado en la aplicación<br>
          Cuando selecciona la opción de cierre de sesión<br>
          Entonces su sesión es terminada de forma segura<br>
          Y es redirigido a una pantalla pública (inicio de sesión o landing page).
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-23</td>
    <td>propietario registrado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de Perfil de Propietario</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario registrado</b>, quiero <b>visualizar mi perfil</b>, para así <b>revisar mi información personal y preferencias almacenadas en el sistema</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Acceso al perfil personal</b><br>
          Dado que que un Propietario está autenticado en el sistema<br>
          Cuando solicita visualizar su perfil<br>
          Entonces se le presenta su información personal registrada, como nombre, correo y teléfono<br>
          Y visualiza sus preferencias de notificación configuradas.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-24</td>
    <td>propietario registrado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Edición de Perfil de Propietario</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario registrado</b>, quiero <b>editar mi información personal y preferencias</b>, para así <b>mantener mi perfil actualizado y tener más control sobre este</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Edición exitosa de información personal</b><br>
          Dado que que un Propietario está en la funcionalidad de edición de perfil<br>
          Cuando modifica su información personal (ej. teléfono) y guarda los cambios<br>
          Entonces sus cambios se almacenan en el sistema<br>
          Y observa un mensaje de confirmación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-25</td>
    <td>Técnico registrado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de Perfil de Técnico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico registrado</b>, quiero <b>visualizar mi perfil profesional</b>, para así <b>revisar cómo se presenta mi información y servicios a los clientes potenciales</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Acceso al perfil profesional</b><br>
          Dado que que un Técnico está autenticado en el sistema<br>
          Cuando solicita visualizar su perfil<br>
          Entonces se le presenta su información profesional tal como la verían los clientes<br>
          Y puede revisar su descripción, certificaciones, portafolio y zonas de cobertura.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-26</td>
    <td>Técnico registrado</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Edición de Perfil de Técnico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico registrado</b>, quiero <b>editar mi información profesional, certificaciones y servicios ofrecidos</b>, para así <b>mantener mi perfil actualizado y atractivo para los clientes</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Edición de información profesional</b><br>
          Dado que que un Técnico está en la funcionalidad de edición de perfil<br>
          Cuando modifica su descripción, información de contacto o especialidades y guarda los cambios<br>
          Entonces sus cambios se almacenan y se reflejan en su perfil público.
        </li>
        <li><b>Escenario #2: Gestión de certificaciones</b><br>
          Dado que que un Técnico está editando su perfil<br>
          Cuando añade una nueva certificación con su respectivo documento<br>
          Entonces la certificación se añade a su perfil y queda pendiente de validación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-27</td>
    <td>usuario de la plataforma</td>
    <td>Media</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Entrar a un dashboard Personalizado</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario de la plataforma</b>, quiero <b>acceder a un dashboard personalizado al iniciar sesión</b>, para así <b>visualizar de forma inmediata la información relevante según mi rol y actividad reciente</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización del dashboard para Propietario</b><br>
          Dado que que un Propietario inicia sesión<br>
          Cuando accede a su panel principal<br>
          Entonces visualiza un resumen de sus servicios activos, sus próximas citas y notificaciones recientes.
        </li>
        <li><b>Escenario #2: Visualización del dashboard para Técnico</b><br>
          Dado que que un Técnico inicia sesión<br>
          Cuando accede a su panel principal<br>
          Entonces visualiza su agenda de servicios del día, solicitudes pendientes y un resumen de sus estadísticas recientes.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-28</td>
    <td>Técnico de servicios eléctricos</td>
    <td>Baja</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Crear Portafolio Digital con Evidencias de Trabajo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico de servicios eléctricos</b>, quiero <b>crear un portafolio digital dentro de mi perfil que incluya fotos, descripciones y referencias de trabajos anteriores</b>, para así <b>mostrar mi experiencia y generar mayor confianza en potenciales clientes</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Añadir un nuevo trabajo al portafolio</b><br>
          Dado que que un Técnico está gestionando su perfil<br>
          Cuando accede a la sección de Portafolio y añade un nuevo trabajo con imágenes y descripción<br>
          Entonces el trabajo se guarda y se muestra en su perfil público.
        </li>
        <li><b>Escenario #2: Organización del portafolio</b><br>
          Dado que que un Técnico tiene varios trabajos en su portafolio<br>
          Cuando organiza sus trabajos por categorías<br>
          Entonces los cambios se reflejan en la vista pública, permitiendo a los clientes filtrar por dichas categorías.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-29</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configuración de Zona de Cobertura Geográfica</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>configurar mi zona de cobertura geográfica especificando radio de acción y ubicaciones donde ofrezco servicios</b>, para así <b>recibir solicitudes solo de clientes dentro de mi área de trabajo</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Definición de una zona de cobertura</b><br>
          Dado que que un Técnico está configurando su perfil operativo<br>
          Cuando define una o más áreas geográficas donde presta servicios<br>
          Entonces el sistema almacena estas zonas<br>
          Y las utilizará para filtrar las solicitudes de servicio que puede recibir.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-30</td>
    <td>usuario de la plataforma</td>
    <td>Media</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configuración de Notificaciones Personalizadas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario de la plataforma</b>, quiero <b>configurar mis preferencias de notificaciones (email, SMS, push) y frecuencia</b>, para así <b>recibir información relevante sin ser saturado de mensajes</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Ajuste de preferencias de notificación</b><br>
          Dado que que un usuario (Propietario o Técnico) está en la configuración de su cuenta<br>
          Cuando ajusta qué tipo de notificaciones desea recibir y por qué canal (ej. email)<br>
          Entonces el sistema guarda sus preferencias<br>
          Y las futuras notificaciones se enviarán de acuerdo a esta configuración.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-31</td>
    <td>técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Crear Componente Eléctrico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico</b>, quiero <b>registrar nuevos componentes eléctricos en mi inventario</b>, para así <b>mantener un inventario completo de mi infraestructura eléctrica</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Registro de un nuevo componente</b><br>
          Dado que que un Técnico está gestionando su inventario<br>
          Cuando proporciona la información de un nuevo componente (nombre, marca, etc.)<br>
          Entonces el sistema registra el nuevo componente en el inventario del técnico.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-32</td>
    <td>técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Editar Componente Eléctrico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico</b>, quiero <b>modificar la información de los componentes eléctricos registrados</b>, para así <b>mantener actualizada la información técnica y de consumo</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Actualización de datos técnicos</b><br>
          Dado que que un Técnico visualiza su inventario<br>
          Cuando selecciona un componente y modifica sus características<br>
          Entonces los cambios se guardan correctamente.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-33</td>
    <td>técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Eliminar Componente Eléctrico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico</b>, quiero <b>eliminar componentes eléctricos de mi inventario</b>, para así <b>mantener actualizada mi configuración cuando retire o reemplace equipos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Eliminación de componente</b><br>
          Dado que que un Técnico visualiza su inventario<br>
          Cuando selecciona un componente y solicita su eliminación<br>
          Entonces el sistema solicita confirmación<br>
          Y elimina el componente del inventario activo tras la confirmación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-34</td>
    <td>propietario</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de Propiedad (Propietario)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario</b>, quiero <b>registrar una nueva propiedad en el sistema, incluyendo su dirección y geolocalización</b>, para así <b>solicitar servicios para ella</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Añadir una nueva propiedad</b><br>
          Dado que que un Propietario está gestionando sus activos<br>
          Cuando proporciona la información de una nueva propiedad, incluyendo su dirección<br>
          Entonces el sistema registra la propiedad y la asocia a su cuenta<br>
          Y la propiedad queda disponible para solicitar servicios.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-35</td>
    <td>propietario</td>
    <td>Media</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Edición de Información de Propiedad (Propietario)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario</b>, quiero <b>editar la información de mis propiedades registradas (ej. dirección, características)</b>, para así <b>mantenerla actualizada</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Actualización de datos de una propiedad</b><br>
          Dado que que un Propietario visualiza sus propiedades registradas<br>
          Cuando selecciona una propiedad y modifica su información<br>
          Entonces los cambios se guardan correctamente.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-36</td>
    <td>propietario</td>
    <td>Media</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Eliminación de Propiedad (Propietario)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario</b>, quiero <b>eliminar una propiedad de mi cuenta</b>, para así <b>registrar otra propiedad</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Eliminación de una propiedad</b><br>
          Dado que que un Propietario visualiza sus propiedades registradas<br>
          Cuando selecciona una propiedad y solicita su eliminación<br>
          Entonces el sistema solicita confirmación<br>
          Y elimina la propiedad de su cuenta tras la confirmación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-37</td>
    <td>Técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de Inventario de Componentes (Técnico)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico</b>, quiero <b>registrar los componentes eléctricos que tengo en mi inventario, incluyendo cantidad y costo</b>, para así <b>controlar mi stock</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Añadir un componente al inventario con stock</b><br>
          Dado que que un Técnico está gestionando su inventario<br>
          Cuando registra un nuevo tipo de componente y especifica la cantidad inicial y el costo<br>
          Entonces el componente se añade a su inventario con el stock correspondiente.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-38</td>
    <td>Técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Actualización de Stock de Componentes (Técnico)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico</b>, quiero <b>actualizar las cantidades de mis componentes en inventario después de una compra o uso en un servicio</b>, para así <b>mantener la precisión del stock</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Ajuste manual de stock</b><br>
          Dado que que un Técnico está gestionando su inventario<br>
          Cuando selecciona un componente y ajusta la cantidad de stock manualmente (ej. por una nueva compra)<br>
          Entonces la cantidad de stock del componente se actualiza.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-39</td>
    <td>Técnico</td>
    <td>Alta</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configuración de Alertas de Stock Mínimo (Técnico)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico</b>, quiero <b>definir umbrales de stock mínimo para mis componentes y recibir alertas cuando el stock alcance ese nivel</b>, para así <b>planificar reposiciones</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Establecer un umbral de stock mínimo</b><br>
          Dado que que un Técnico está gestionando un componente en su inventario<br>
          Cuando establece un umbral numérico de stock mínimo para ese componente<br>
          Entonces el sistema guarda esta configuración.
        </li>
        <li><b>Escenario #2: Recepción de alerta</b><br>
          Dado que que un componente tiene un umbral de stock mínimo configurado<br>
          Cuando el stock de ese componente baja hasta o por debajo del umbral<br>
          Entonces el sistema envía una notificación al Técnico informando de la situación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-40</td>
    <td>propietario de PyME</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Contratación de Servicios Eléctricos mediante Wizard</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario de PyME</b>, quiero <b>contar con un proceso guiado paso a paso para contratar servicios eléctricos</b>, para así <b>solucionar mis problemas de forma rápida y sin complicaciones</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Completar proceso guiado</b><br>
          Dado que que un Propietario inicia el proceso de contratación<br>
          Cuando completa todos los pasos requeridos en el asistente (selección de propiedad, servicio, etc.)<br>
          Entonces el sistema genera una solicitud de servicio<br>
          Y le confirma que la solicitud ha sido creada y está pendiente de asignación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-41</td>
    <td>propietario con múltiples propiedades</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Selección de Propiedad</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario con múltiples propiedades</b>, quiero <b>seleccionar la propiedad específica donde necesito el servicio</b>, para así <b>que el sistema asigne al técnico más cercano a esa ubicación</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Selección de propiedad en la solicitud</b><br>
          Dado que que un Propietario con más de una propiedad inicia una solicitud de servicio<br>
          Cuando el sistema le solicita indicar para qué propiedad es el servicio<br>
          Entonces puede seleccionar una de sus propiedades registradas<br>
          Y la ubicación de esa propiedad será utilizada para la asignación del técnico.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-42</td>
    <td>propietario solicitando un servicio</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Carga Manual de Datos de Recibos Eléctricos (3-6 recibos)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario solicitando un servicio</b>, quiero <b>ingresar manualmente los datos clave de mi último recibo eléctrico durante el proceso de solicitud</b>, para así <b>registrar mi historial de consumo y permitir análisis a largo plazo en mi panel de Analytics</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Ingreso de datos del recibo</b><br>
          Dado que que un Propietario está en el proceso de solicitar un servicio<br>
          Cuando ingresa los datos de consumo (kWh, monto, período) de su recibo eléctrico<br>
          Entonces el sistema valida y asocia esta información a la solicitud<br>
          Y los datos quedan almacenados para su futuro análisis de consumo.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-43</td>
    <td>propietario que ya ha seleccionado un servicio</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Descripción Detallada del Problema Eléctrico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario que ya ha seleccionado un servicio</b>, quiero <b>añadir una descripción detallada de mi problema</b>, para así <b>que el técnico asignado conozca el contexto específico antes de su llegada</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Añadir detalles a la solicitud</b><br>
          Dado que que un Propietario está creando una solicitud de servicio<br>
          Cuando proporciona texto adicional describiendo el problema<br>
          Entonces esta descripción se adjunta a la solicitud y será visible para el técnico que sea asignado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-44</td>
    <td>propietario</td>
    <td>Alta</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Selección de Servicio Específico del Catálogo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario</b>, después de seleccionar mi propiedad, quiero <b>ver una lista de servicios específicos disponibles en mi zona (ej: 'Instalación de tomacorriente', 'Diagnóstico General') y seleccionar el que necesito</b>, para así <b>que el sistema sepa exactamente qué trabajo solicitar y pueda automatizar la asignación</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Selección de un servicio del catálogo</b><br>
          Dado que que un Propietario ha seleccionado la propiedad para el servicio<br>
          Cuando el sistema le presenta el catálogo de servicios disponibles en su zona<br>
          Entonces puede seleccionar un servicio específico de la lista<br>
          Y la solicitud queda vinculada a ese servicio del catálogo.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-45</td>
    <td>cliente</td>
    <td>Alta</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Cancelación de servicios programados</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>cliente</b>, quiero <b>cancelar un servicio programado con anticipación</b>, para así <b>evitar cargos innecesarios</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Cancelación dentro del plazo permitido</b><br>
          Dado que que un Propietario tiene un servicio programado<br>
          Cuando solicita cancelarlo dentro del plazo permitido por las políticas<br>
          Entonces el sistema procesa la cancelación sin penalización<br>
          Y notifica tanto al Propietario como al Técnico asignado.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-46</td>
    <td>propietario</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Notificación de Asignación Automática de Técnico (Propietario)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario</b>, después de que mi solicitud de servicio es asignada automáticamente, quiero <b>recibir una notificación con la información del técnico asignado</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Recepción de notificación de asignación</b><br>
          Dado que que un Propietario ha creado una solicitud de servicio<br>
          Cuando el sistema asigna automáticamente un Técnico al servicio<br>
          Entonces el Propietario recibe una notificación<br>
          Y la notificación contiene la información del perfil del Técnico asignado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-47</td>
    <td>cliente</td>
    <td>Alta</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Historial de servicios contratados</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>cliente</b>, quiero <b>ver un historial de los servicios que he contratado anteriormente</b>, para así <b>referencia futura</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización de historial de servicios</b><br>
          Dado que que un Propietario accede a su historial de servicios<br>
          Cuando no aplica ningún filtro<br>
          Entonces visualiza todos los servicios contratados ordenados cronológicamente<br>
          Y para cada servicio puede ver detalles como fecha, técnico y estado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-48</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configurar Horarios de Trabajo Semanales</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>configurar mis horarios de trabajo por día de la semana (ej: Lunes 8AM-6PM, Martes 10AM-4PM) y definir la duración promedio que me toma cada tipo de servicio</b>, para así <b>que el sistema pueda asignarme automáticamente trabajos solo en mis horarios laborales disponibles</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Establecer disponibilidad semanal</b><br>
          Dado que que un Técnico está configurando su agenda<br>
          Cuando define sus horas de trabajo para cada día de la semana<br>
          Entonces el sistema guarda esta disponibilidad como su horario laboral estándar<br>
          Y lo usará como criterio para la asignación automática de servicios.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-49</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Modificar Horarios de Trabajo Existentes</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>modificar mis horarios de trabajo ya configurados (cambiar horas de inicio/fin, días laborales)</b>, para así <b>ajustar mi disponibilidad según cambios en mi situación personal o comercial</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Ajustar disponibilidad semanal</b><br>
          Dado que que un Técnico tiene un horario de trabajo configurado<br>
          Cuando modifica las horas de inicio o fin de un día laboral y guarda los cambios<br>
          Entonces el sistema actualiza su horario laboral estándar.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-50</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Bloquear Fechas y Horarios Específicos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>bloquear fechas específicas (vacaciones, emergencias) o horarios puntuales (citas médicas, otros compromisos) en mi calendario</b>, para así <b>evitar que el sistema me asigne trabajos durante esos períodos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Bloquear un período de tiempo</b><br>
          Dado que que un Técnico está gestionando su agenda<br>
          Cuando selecciona una fecha o un rango de horas y lo marca como no disponible<br>
          Entonces el sistema registra este bloqueo<br>
          Y no le asignará servicios durante ese período.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-51</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualizar Agenda de Trabajos Asignados Automáticamente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>visualizar en un calendario todos los trabajos que el sistema me ha asignado automáticamente dentro de mis horarios disponibles</b>, para así <b>planificar mi día y ver mi carga de trabajo semanal</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Vista de agenda con trabajos asignados</b><br>
          Dado que que un Técnico accede a su agenda<br>
          Cuando tiene trabajos que le han sido asignados<br>
          Entonces visualiza estos trabajos en una vista de calendario<br>
          Y puede ver los detalles de cada servicio programado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-52</td>
    <td>técnico registrado</td>
    <td>Media</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configurar Tiempo de Traslado Entre Servicios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>configurar el tiempo promedio que necesito para trasladarme entre ubicaciones en mi zona de cobertura</b>, para así <b>que el sistema considere estos intervalos al asignarme trabajos consecutivos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Configurar buffer de traslado</b><br>
          Dado que que un Técnico está configurando su agenda<br>
          Cuando define un tiempo promedio de traslado (ej. 30 minutos)<br>
          Entonces el sistema considerará este intervalo de tiempo entre servicios consecutivos al momento de la asignación automática.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-53</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Crear Servicios en Catálogo con Recetas de Componentes</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>crear nuevos servicios en mi catálogo especificando qué componentes eléctricos exactos necesito y en qué cantidades (receta)</b>, para así <b>que el sistema verifique automáticamente si tengo stock suficiente antes de asignarme ese tipo de trabajo</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Crear un servicio con receta</b><br>
          Dado que que un Técnico está gestionando su catálogo<br>
          Cuando crea un nuevo servicio y le asocia una "receta" (lista de componentes y cantidades de su inventario)<br>
          Entonces el servicio se guarda con su receta de componentes asociada<br>
          Y el sistema usará esta receta para validar el stock antes de la asignación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-54</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Modificar Servicios y sus Recetas de Componentes</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>modificar los servicios existentes en mi catálogo (precio, descripción, componentes necesarios)</b>, para así <b>mantener actualizada mi oferta y las recetas de materiales</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Actualizar una receta de servicio</b><br>
          Dado que que un Técnico está editando un servicio existente con receta<br>
          Cuando modifica la lista de componentes o sus cantidades<br>
          Entonces la receta del servicio se actualiza.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-55</td>
    <td>técnico registrado</td>
    <td>Alta</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Eliminar Servicios del Catálogo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>eliminar servicios que ya no ofrezco de mi catálogo</b>, para así <b>evitar que el sistema me asigne trabajos que no puedo realizar</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Eliminación de un servicio</b><br>
          Dado que que un Técnico visualiza su catálogo de servicios<br>
          Cuando selecciona un servicio y solicita su eliminación<br>
          Entonces el servicio se elimina y ya no será ofrecido a los clientes.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-56</td>
    <td>técnico registrado</td>
    <td>Media</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Establecimiento Precios por Tipo de Servicio y Zona</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico registrado</b>, quiero <b>establecer precios diferenciados por tipo de servicio y opcionalmente por zona dentro de mi área de cobertura</b>, para así <b>tener una estructura tarifaria clara y rentable</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Definir precio de un servicio</b><br>
          Dado que que un Técnico está creando o editando un servicio<br>
          Cuando establece un precio base para dicho servicio<br>
          Entonces ese precio se mostrará a los clientes como referencia.
        </li>
        <li><b>Escenario #2: Definir precio diferenciado por zona (opcional)</b><br>
          Dado que que un Técnico ha definido múltiples zonas de cobertura<br>
          Cuando edita un servicio<br>
          Entonces puede opcionalmente establecer un precio diferente para una zona específica.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-57</td>
    <td>propietario con suscripción Premium</td>
    <td>Baja</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Beneficio de Solicitud Prioritaria</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario con suscripción Premium</b>, al crear una solicitud de servicio, quiero <b>tener disponible y activar la opción de "marcar como prioritaria"</b>, para así <b>que mi solicitud tenga preferencia en el sistema de asignación y así resolver mi problema más rápidamente</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Marcar solicitud como prioritaria</b><br>
          Dado que que un Propietario con plan Premium está creando una solicitud<br>
          Cuando activa la opción de solicitud prioritaria<br>
          Entonces la solicitud es creada y marcada con alta prioridad para el proceso de asignación.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-58</td>
    <td>propietario del plan Básico</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Notificación de Límite de Solicitudes Alcanzado</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario del plan Básico</b>, al intentar crear una solicitud que excede mi límite mensual (2), quiero <b>ser notificado claramente por el sistema y ver una opción directa para mejorar mi plan a Premium</b>, para así <b>entender las reglas del plan gratuito y continuar usando el servicio si lo necesito</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Bloqueo por límite de solicitudes</b><br>
          Dado que que un Propietario con plan Básico ya ha alcanzado su límite de solicitudes mensuales<br>
          Cuando intenta crear una nueva solicitud de servicio<br>
          Entonces el sistema le impide continuar<br>
          Y le informa que ha alcanzado su límite<br>
          Y le presenta la opción de actualizar a un plan superior.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-59</td>
    <td>propietario y técnico</td>
    <td>Media</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Seguimiento de Estados de Servicio en Tiempo Real</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>propietario y técnico</b>, quiero <b>ver el estado actual del servicio (programado, confirmado, en progreso, completado) actualizado en tiempo real</b>, para así <b>estar informado sobre el progreso del trabajo</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Visualización del estado del servicio</b><br>
          Dado que que un servicio ha sido asignado<br>
          Cuando el Propietario o el Técnico consultan los detalles del servicio<br>
          Entonces visualizan el estado actual del mismo (ej. "Programado").
        </li>
        <li><b>Escenario #2: Actualización del estado</b><br>
          Dado que que un Técnico está ejecutando un servicio<br>
          Cuando actualiza el estado del servicio a "En Progreso"<br>
          Entonces el nuevo estado es visible tanto para él como para el Propietario.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-60</td>
    <td>técnico ejecutando un servicio</td>
    <td>Media</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro Fotográfico de Trabajos (Antes/Después)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico ejecutando un servicio</b>, quiero <b>tomar y subir fotografías del área de trabajo antes y después de la intervención</b>, para así <b>documentar el trabajo realizado y protegerme ante reclamos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Adjuntar evidencia fotográfica</b><br>
          Dado que que un Técnico está gestionando un servicio activo<br>
          Cuando sube fotografías correspondientes al "antes" y "después" del trabajo<br>
          Entonces las imágenes quedan asociadas al registro del servicio como evidencia.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-61</td>
    <td>técnico completando un servicio</td>
    <td>Media</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Generación de Reportes Técnicos Estructurados</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico completando un servicio</b>, quiero <b>generar un reporte técnico estructurado que incluya los componentes utilizados de la 'receta' original, los procedimientos realizados y recomendaciones</b>, para así <b>profesionalizar mi servicio y dejar constancia del trabajo</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Generar un reporte de servicio</b><br>
          Dado que que un Técnico ha completado un servicio<br>
          Cuando finaliza el trabajo y accede a la funcionalidad de reporte<br>
          Entonces puede documentar los componentes utilizados, el trabajo realizado y las recomendaciones para el cliente<br>
          Y este reporte queda asociado al historial del servicio.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-62</td>
    <td>técnico que completa un servicio</td>
    <td>Alta</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Actualización Automática de Inventario Post-Servicio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>técnico que completa un servicio</b>, quiero <b>que el sistema descuente automáticamente del mi inventario los componentes que marqué como utilizados en el reporte técnico</b>, para así <b>mantener mi stock actualizado sin trabajo manual</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Descuento automático de stock</b><br>
          Dado que que un Técnico ha completado un servicio que tenía una "receta" de componentes<br>
          Cuando marca el servicio como "Completado" y confirma los componentes utilizados en el reporte<br>
          Entonces el sistema descuenta automáticamente las cantidades de esos componentes de su inventario.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-63</td>
    <td>Técnico</td>
    <td>Media</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Historial de Clientes Atendidos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico</b>, quiero <b>acceder a un historial detallado de los clientes que he atendido</b>, para así <b>dar seguimiento a relaciones profesionales y mejorar mi servicio basado en experiencias previas</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Consulta de historial de clientes</b><br>
          Dado que que un Técnico ha completado servicios<br>
          Cuando accede a su historial de clientes<br>
          Entonces puede visualizar un listado de todos los clientes atendidos<br>
          Y para cada cliente, puede ver los servicios prestados.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-64</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Sistema de Calificación Post-Servicio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>calificar y dejar reseñas sobre los servicios que he utilizado</b>, para así <b>compartir mi experiencia con otros usuarios y proporcionar retroalimentación a los Técnicos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Calificación del servicio</b><br>
          Dado que que un Propietario ha recibido un servicio que ya fue marcado como "Completado"<br>
          Cuando completa el formulario de calificación (puntuación y comentarios)<br>
          Entonces el sistema registra su calificación y la asocia al servicio y al perfil del Técnico.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-65</td>
    <td>usuario</td>
    <td>Baja</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Visualización de Calificaciones y Reseñas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>usuario</b>, quiero <b>ver las calificaciones y reseñas dejadas por otros usuarios</b>, para así <b>tomar decisiones informadas sobre qué servicios utilizar</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Consulta de la reputación de un técnico</b><br>
          Dado que que un Propietario está explorando el perfil de un Técnico<br>
          Cuando accede a la sección de reseñas<br>
          Entonces visualiza la calificación promedio y los comentarios dejados por otros usuarios.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-66</td>
    <td>Técnico</td>
    <td>Baja</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Retroalimentación directa de servicios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>Técnico</b>, quiero <b>recibir retroalimentación directa sobre mis servicios</b>, para así <b>mejorar mi oferta</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario #1: Revisión de valoraciones recibidas</b><br>
          Dado que que un Técnico ha recibido valoraciones por sus servicios<br>
          Cuando accede a su sección de retroalimentación<br>
          Entonces puede ver todas las valoraciones recibidas de sus clientes<br>
          Y puede identificar los aspectos mejor y peor valorados.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-01</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-12</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registrar Propiedad</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint POST para registrar una propiedad asociada a un propietario</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso</b><br>
          Dado que el usuario está autenticado<br>
          Cuando envía un request POST con todos los datos válidos de su propiedad<br>
          Entonces el sistema responde con un estado 201 Created<br>
          Y el cuerpo de la respuesta incluye la propiedad recién creada.
        </li>
        <li><b>Escenario 2: Faltan datos obligatorios</b><br>
          Dado que el usuario omite el campo "dirección"<br>
          Cuando intenta registrar la propiedad<br>
          Entonces el sistema responde con un error 400 Bad Request y un mensaje de validación.
        </li>
        <li><b>Escenario 3: Usuario no autenticado</b><br>
          Dado que un usuario no autenticado intenta acceder al endpoint<br>
          Cuando envía un request POST<br>
          Entonces el sistema responde con un error 401 Unauthorized.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-02</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-12</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Obtener Propiedades por Propietario</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint GET para listar todas las propiedades registradas por un propietario</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Propietario con propiedades</b><br>
          Dado que el propietario está autenticado y tiene propiedades registradas<br>
          Cuando consulta el endpoint<br>
          Entonces se devuelve un estado 200 OK y una lista con sus propiedades.
        </li>
        <li><b>Escenario 2: Propietario sin propiedades</b><br>
          Dado que el propietario está autenticado pero no tiene propiedades registradas<br>
          Cuando consulta el endpoint<br>
          Entonces se devuelve un estado 200 OK y una lista vacía [].
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-03</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-13</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Crear Componente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint POST para que el técnico registre un nuevo componente en su inventario</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Creación exitosa</b><br>
          Dado que un técnico autenticado envía la información completa del componente<br>
          Cuando se recibe el request POST<br>
          Entonces el sistema responde con 201 Created y el nuevo componente.
        </li>
        <li><b>Escenario 2: Componente duplicado</b><br>
          Dado que el técnico intenta crear un componente con un nombre que ya existe en su inventario<br>
          Cuando envía el request<br>
          Entonces el sistema responde con 409 Conflict y un mensaje de error.
        </li>
        <li><b>Escenario 3: Acceso no autorizado por rol</b><br>
          Dado que un usuario con rol "Propietario" intenta crear un componente<br>
          Cuando envía el request<br>
          Entonces el sistema responde con un error 403 Forbidden.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-04</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-13</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Actualizar Stock de Componente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint PATCH para actualizar el stock de un componente del inventario del técnico</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Actualización exitosa</b><br>
          Dado que un técnico quiere modificar la cantidad de un componente existente<br>
          Cuando envía un nuevo valor de stock<br>
          Entonces se responde con 200 OK y se actualiza el stock en la base de datos.
        </li>
        <li><b>Escenario 2: Componente inexistente</b><br>
          Dado que el técnico intenta actualizar un componente con un ID que no existe<br>
          Cuando envía el request<br>
          Entonces el sistema responde con un error 404 Not Found.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-05</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-13</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Crear Servicio de Técnico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint POST para que el técnico defina un nuevo servicio en su catálogo, incluyendo su "receta" de componentes</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Creación exitosa</b><br>
          Dado que un técnico autenticado envía datos válidos para un nuevo servicio y su receta<br>
          Cuando se recibe la solicitud POST<br>
          Entonces el sistema responde con 201 Created y el nuevo servicio.
        </li>
        <li><b>Escenario 2: Faltan datos obligatorios</b><br>
          Dado que el técnico envía los datos del servicio pero sin la "receta"<br>
          Cuando se recibe la solicitud POST<br>
          Entonces el sistema responde con 400 Bad Request y un error de validación.
        </li>
        <li><b>Escenario 3: Componente de la receta no existe</b><br>
          Dado que el técnico incluye en la receta un ID de componente que no es válido<br>
          Cuando se recibe la solicitud POST<br>
          Entonces el sistema responde con 400 Bad Request y un error específico.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-06</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-14</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Obtener Servicios por Zona</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint GET que devuelva los servicios disponibles en una zona geográfica específica</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Servicios encontrados</b><br>
          Dado que un propietario consulta una zona con cobertura de técnicos<br>
          Cuando el frontend consulta con la ubicación de la propiedad<br>
          Entonces el sistema devuelve 200 OK y una lista de servicios únicos.
        </li>
        <li><b>Escenario 2: Zona sin cobertura</b><br>
          Dado que la ubicación de la propiedad no está en la zona de cobertura de ningún técnico<br>
          Cuando se realiza la consulta<br>
          Entonces el sistema responde con 200 OK y una lista vacía [].
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-07</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-14</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Iniciar Flujo de Solicitud</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint que valide el plan del propietario al iniciar una solicitud</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Usuario gratuito dentro del límite</b><br>
          Dado que un propietario con plan gratuito ha hecho 1 solicitud este mes<br>
          Cuando inicia una nueva solicitud<br>
          Entonces el sistema responde 200 OK y le permite continuar.
        </li>
        <li><b>Escenario 2: Usuario gratuito alcanza el límite</b><br>
          Dado que el propietario con plan gratuito ya ha hecho 2 solicitudes este mes<br>
          Cuando inicia una nueva solicitud<br>
          Entonces el sistema responde 403 Forbidden y sugiere actualizar a Premium.
        </li>
        <li><b>Escenario 3: Usuario Premium sin límites</b><br>
          Dado que un propietario con plan Premium ha hecho 5 solicitudes este mes<br>
          Cuando inicia una nueva solicitud<br>
          Entonces el sistema responde 200 OK y le permite continuar.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-08</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-14</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Enviar Solicitud de Servicio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint POST que registre los detalles de una solicitud de servicio</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Envío exitoso</b><br>
          Dado que el propietario ha completado el asistente<br>
          Cuando envía los datos finales de la solicitud<br>
          Entonces el sistema responde 201 Created y guarda la solicitud.
        </li>
        <li><b>Escenario 2: Faltan datos de recibo</b><br>
          Dado que se omiten datos obligatorios del recibo<br>
          Cuando se envía la solicitud<br>
          Entonces el sistema responde 400 Bad Request con un error de validación.
        </li>
        <li><b>Escenario 3: Usuario gratuito intenta usar prioridad</b><br>
          Dado que un propietario con plan gratuito marca la solicitud como prioritaria<br>
          Cuando envía la solicitud<br>
          Entonces el sistema responde 403 Forbidden y un mensaje de error.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-09</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-14</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Asignar Técnico Automáticamente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>implementar la lógica para asignar automáticamente un técnico a una solicitud</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Asignación exitosa</b><br>
          Dado que hay una solicitud pendiente y un técnico compatible<br>
          Cuando se activa el proceso de asignación<br>
          Entonces se asigna el técnico a la solicitud y se actualiza su estado a "asignado".
        </li>
        <li><b>Escenario 2: Ningún técnico compatible</b><br>
          Dado que ningún técnico cumple con los criterios de stock o agenda<br>
          Cuando se intenta asignar<br>
          Entonces la solicitud permanece en estado "pendiente" y se registra el fallo.
        </li>
        <li><b>Escenario 3: Asignación con prioridad</b><br>
          Dado que hay una solicitud normal y una prioritaria, y un solo técnico disponible<br>
          Cuando se activa la asignación<br>
          Entonces el sistema asigna el técnico a la solicitud prioritaria primero.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-10</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-13</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Actualización Automática de Stock</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un listener que reaccione al evento "Servicio Completado" para descontar el stock</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Descuento exitoso</b><br>
          Dado que un servicio es "Completado" y se publica el evento con los componentes usados<br>
          Cuando el listener recibe el evento<br>
          Entonces el sistema actualiza el inventario del técnico correctamente.
        </li>
        <li><b>Escenario 2: El evento no contiene componentes</b><br>
          Dado que se recibe un evento "Servicio Completado" sin componentes listados<br>
          Cuando el listener lo procesa<br>
          Entonces el proceso termina exitosamente sin realizar cambios en el inventario.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-11</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-15</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Enviar Evaluación de Servicio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint POST para registrar una evaluación</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Evaluación exitosa</b><br>
          Dado que un servicio está "Completado"<br>
          Cuando el usuario envía una evaluación válida<br>
          Entonces se responde 201 Created y se guarda la evaluación.
        </li>
        <li><b>Escenario 2: Servicio no completado</b><br>
          Dado que un usuario intenta evaluar un servicio "En progreso"<br>
          Cuando se envía el request<br>
          Entonces el sistema responde 403 Forbidden y un mensaje adecuado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-12</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-15</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Obtener Evaluaciones por Técnico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint GET para obtener las evaluaciones de un técnico</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Técnico con evaluaciones</b><br>
          Dado que un técnico tiene evaluaciones registradas<br>
          Cuando se hace la consulta<br>
          Entonces el sistema responde 200 OK con la lista de evaluaciones.
        </li>
        <li><b>Escenario 2: Técnico sin evaluaciones</b><br>
          Dado que el técnico aún no ha recibido evaluaciones<br>
          Cuando se hace la consulta<br>
          Entonces el sistema responde 200 OK con una lista vacía.
        </li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-13</td>
    <td>desarrollador</td>
    <td>Alta</td>
    <td>EP-00</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Conectar a Base de Datos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>configurar la conexión a la base de datos PostgreSQL</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Conexión exitosa</b><br>
          Dado que las credenciales de la base de datos son correctas<br>
          Cuando se levanta el servidor<br>
          Entonces la conexión se establece sin errores.
        </li>
        <li><b>Escenario 2: Credenciales incorrectas</b><br>
          Dado que la contraseña de la base de datos es incorrecta<br>
          Cuando el servidor intenta conectarse<br>
          Entonces el sistema lanza un error de autenticación y detiene el arranque.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-14</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Listener de Webhook de Stripe</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint para recibir y procesar webhooks de Stripe</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Suscripción exitosa</b><br>
          Dado que un usuario completa un pago en Stripe<br>
          Cuando Stripe envía el evento "checkout.session.completed"<br>
          Entonces el sistema valida la firma y actualiza el estado del usuario a "Premium".
        </li>
        <li><b>Escenario 2: Firma de Webhook inválida</b><br>
          Dado que se recibe un request con una firma de Stripe incorrecta<br>
          Cuando el sistema intenta validar el evento<br>
          Entonces rechaza el request con un error 400 Bad Request.
        </li>
        <li><b>Escenario 3: Evento de cancelación de suscripción</b><br>
          Dado que un usuario cancela su plan desde el portal de Stripe<br>
          Cuando Stripe envía el evento "customer.subscription.deleted"<br>
          Entonces el sistema actualiza el estado del usuario a "Básico".
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-15</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Reinicio Mensual de Contador</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear una tarea programada (cron job) que se ejecute mensualmente</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Reseteo exitoso</b><br>
          Dado que es el primer día del mes<br>
          Cuando se ejecuta la tarea<br>
          Entonces el sistema reinicia el contador de solicitudes de todos los usuarios del plan gratuito.
        </li>
        <li><b>Escenario 2: Tarea se ejecuta en día incorrecto</b><br>
          Dado que no es el primer día del mes<br>
          Cuando la tarea se ejecuta (por un error o test)<br>
          Entonces el proceso termina sin realizar ninguna acción.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-16</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Sesión de Portal de Stripe</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint que genere una sesión para el Portal de Cliente de Stripe</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Generación exitosa</b><br>
          Dado que un usuario Premium autenticado solicita gestionar su plan<br>
          Cuando se consulta el endpoint<br>
          Entonces se genera y devuelve una URL única para el portal de Stripe.
        </li>
        <li><b>Escenario 2: Usuario no suscrito</b><br>
          Dado que un usuario del plan gratuito intenta acceder al portal<br>
          Cuando se consulta el endpoint<br>
          Entonces el sistema responde 403 Forbidden.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-17</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Endpoint de Autenticación JWT</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un endpoint de login que genere tokens JWT para permitir la autenticación segura de usuarios</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Login exitoso</b><br>
          Dado que se envía POST /api/auth/login con email y password válidos<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna un token JWT<br>
          Y el token incluye el rol del usuario<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 2: Credenciales inválidas</b><br>
          Dado que se envía POST /api/auth/login con credenciales incorrectas<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna error 401<br>
          Y retorna mensaje de error apropiado.
        </li>
        <li><b>Escenario 3: Validación de token</b><br>
          Dado que se envía una petición con token JWT en header Authorization<br>
          Cuando se valida el token<br>
          Entonces el sistema verifica la firma del token<br>
          Y retorna la información del usuario si es válido.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-18</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Endpoint de Registro de Usuarios</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear endpoints de registro diferenciados para permitir el registro de propietarios y técnicos</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso de propietario</b><br>
          Dado que se envía POST /api/auth/register/owner con datos válidos<br>
          Cuando se procesa la petición<br>
          Entonces el sistema crea el usuario con rol "owner"<br>
          Y encripta la contraseña<br>
          Y retorna código 201<br>
          Y retorna el usuario creado (sin contraseña).
        </li>
        <li><b>Escenario 2: Registro exitoso de técnico</b><br>
          Dado que se envía POST /api/auth/register/technician con datos válidos<br>
          Cuando se procesa la petición<br>
          Entonces el sistema crea el usuario con rol "technician"<br>
          Y almacena las certificaciones básicas<br>
          Y retorna código 201.
        </li>
        <li><b>Escenario 3: Email duplicado</b><br>
          Dado que se intenta registrar con email ya existente<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna error 409<br>
          Y retorna mensaje indicando email duplicado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-19</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Verificación de Email</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear endpoints para verificar emails de usuarios para completar el proceso de registro</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Generar token de verificación</b><br>
          Dado que se registra un nuevo usuario<br>
          Cuando se completa el registro<br>
          Entonces el sistema genera un token de verificación<br>
          Y almacena el token en base de datos<br>
          Y marca el usuario como "no verificado".
        </li>
        <li><b>Escenario 2: Verificar email</b><br>
          Dado que se envía GET /api/auth/verify/{token}<br>
          Cuando se procesa la petición con token válido<br>
          Entonces el sistema marca el usuario como verificado<br>
          Y retorna código 200<br>
          Y retorna mensaje de confirmación.
        </li>
        <li><b>Escenario 3: Token inválido</b><br>
          Dado que se envía un token de verificación inválido<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna error 400<br>
          Y retorna mensaje de token inválido.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-20</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Middleware de Autorización</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear middleware de autorización para controlar acceso a endpoints según roles de usuario</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Acceso autorizado</b><br>
          Dado que un usuario con rol correcto accede a un endpoint protegido<br>
          Cuando el middleware verifica los permisos<br>
          Entonces el sistema permite continuar con la petición<br>
          Y pasa al siguiente middleware o controlador.
        </li>
        <li><b>Escenario 2: Acceso denegado por rol</b><br>
          Dado que un usuario sin permisos accede a endpoint restringido<br>
          Cuando el middleware verifica los permisos<br>
          Entonces el sistema retorna error 403<br>
          Y retorna mensaje de acceso denegado.
        </li>
        <li><b>Escenario 3: Token faltante</b><br>
          Dado que se accede a endpoint protegido sin token<br>
          Cuando el middleware verifica autenticación<br>
          Entonces el sistema retorna error 401<br>
          Y retorna mensaje de token requerido.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-21</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Recuperación de Contraseña</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear endpoints para recuperación de contraseña para permitir a usuarios restablecer sus credenciales</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Solicitar recuperación</b><br>
          Dado que se envía POST /api/auth/forgot-password con email válido<br>
          Cuando se procesa la petición<br>
          Entonces el sistema genera un token de recuperación<br>
          Y almacena el token con expiración<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 2: Restablecer contraseña</b><br>
          Dado que se envía POST /api/auth/reset-password con token y nueva contraseña<br>
          Cuando se procesa la petición con token válido<br>
          Entonces el sistema actualiza la contraseña encriptada<br>
          Y elimina el token de recuperación<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 3: Token expirado</b><br>
          Dado que se intenta usar un token de recuperación expirado<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna error 400<br>
          Y retorna mensaje de token expirado.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-22</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Endpoints de Gestión de Perfiles</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear endpoints CRUD para gestión de perfiles para permitir a usuarios actualizar su información personal</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Obtener perfil</b><br>
          Dado que se envía GET /api/users/profile con token válido<br>
          Cuando se procesa la petición<br>
          Entonces el sistema retorna la información del usuario<br>
          Y omite campos sensibles como contraseña<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 2: Actualizar perfil</b><br>
          Dado que se envía PUT /api/users/profile con datos válidos<br>
          Cuando se procesa la petición<br>
          Entonces el sistema actualiza los campos permitidos<br>
          Y retorna el perfil actualizado<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 3: Datos inválidos</b><br>
          Dado que se envían datos inválidos en actualización<br>
          Cuando se validan los datos<br>
          Entonces el sistema retorna error 400<br>
          Y retorna lista de errores de validación por campo.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Story ID</th>
    <th>Role</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-23</td>
    <td>desarrollador</td>
    <td>Baja</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Sistema de Notificaciones Básico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">
      Como un <b>desarrollador</b>, quiero <b>crear un servicio básico de notificaciones para enviar emails simples a los usuarios</b>.
    </td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Enviar email simple</b><br>
          Dado que se requiere enviar un email<br>
          Cuando se llama al servicio de notificaciones<br>
          Entonces el sistema envía el email usando configuración SMTP<br>
          Y registra el envío en logs<br>
          Y retorna confirmación de envío.
        </li>
        <li><b>Escenario 2: Configurar preferencias</b><br>
          Dado que se envía PUT /api/users/notifications con preferencias<br>
          Cuando se procesa la petición<br>
          Entonces el sistema actualiza las preferencias del usuario<br>
          Y retorna código 200.
        </li>
        <li><b>Escenario 3: Error en envío</b><br>
          Dado que falla el envío de email<br>
          Cuando se detecta el error<br>
          Entonces el sistema registra el error en logs<br>
          Y retorna error apropiado al llamador.
        </li>
      </ul>
    </td>
  </tr>
</table>


## 3.3. Impact Mapping

Un mapa de impacto es una técnica colaborativa y visual de planificación estratégica que alinea los objetivos de un proyecto con las acciones necesarias para alcanzarlos. En este sección , el equipo presenta los mapas de impacto realizados.

<hr>

<img src="https://i.postimg.cc/jjHPVLW0/asdasd.png"/>
<hr>



<img src="https://i.postimg.cc/Dz0060qP/rwerwetre.png"/>
<hr>



<img src="https://i.postimg.cc/8P7Z2mN2/asdasda.png"/>
<hr>

## 3.4. Product Backlog

El product backlog es una lista priorizada, dinámica y evolutiva de requisitos, funcionalidades, mejoras y correcciones necesarias para el desarrollo de un producto. En esta sección, el equipo establecio el product backlog de acuerdo al peso en story points de cada historia sea tecnica o de usuario.

<hr>

# 

| StoryID | Título | Descripción | Story Points (1/3/5/8) |
|---------|--------|-------------|------------------------|
| US-08 | Ver Información del Startup | Como potencial cliente, quiero conocer información sobre la empresa desarrolladora, para evaluar su credibilidad y confiabilidad. | 1 |
| US-09 | Conocer la Misión de la Startup | Como visitante interesado, quiero conocer la misión de la empresa, para entender sus valores y propósito. | 1 |
| US-10 | Conocer la Visión de la Startup | Como visitante interesado, quiero conocer la visión de la empresa, para entender sus objetivos a largo plazo y su proyección de futuro. | 1 |
| US-04 | Visualización de una Sección Principal | Como visitante de la página, quiero ver una sección principal atractiva que me presente un breve resumen de la idea del producto, para entender rápidamente de qué se trata el servicio. | 2 |
| US-05 | Navegación sin errores | Como visitante, quiero navegar por la página web sin encontrar errores, para tener una experiencia fluida que me anime a registrarme. | 2 |
| US-06 | Navegación mediante Encabezado | Como usuario, quiero un menú de navegación claro en el encabezado, para acceder fácilmente a las diferentes secciones de la página. | 2 |
| US-07 | Visualización del Pie de página | Como visitante, quiero ver un pie de página organizado con accesos directos e información de contacto, para encontrar información adicional rápidamente. | 2 |
| US-19 | Mensajes de éxito retroalimentación de registro | Como usuario, quiero recibir mensajes claros y accesibles al completar el registro sobre éxito para entender fácilmente el resultado de mis acciones. | 2 |
| US-20 | Mensajes de error retroalimentación de registro | Como usuario, quiero recibir mensajes claros y accesibles al completar el registro sobre cualquier error a la hora de completar el formulario, para entender fácilmente el resultado de mis acciones y saber cómo proceder. | 2 |
| US-22 | Cierre de Sesión | Como usuario autenticado, quiero cerrar mi sesión de forma segura para proteger mi cuenta cuando termine de usar la aplicación. | 2 |
| US-01 | Visualización de Características y Beneficios | Como visitante de la landing page, Quiero ver claramente las características y beneficios de la plataforma, Para entender cómo puede ayudarme y decidir si registrarme. | 3 |
| US-02 | Visualización de Testimonios | Como visitante indeciso sobre la plataforma, Quiero ver testimonios de usuarios reales, Para aumentar mi confianza en el servicio antes de registrarse. | 3 |
| US-03 | Adaptabilidad a Diferentes Dispositivos | Como visitante que accede desde diferentes dispositivos, Quiero que la landing page se adapte correctamente a mi pantalla, Para tener una experiencia óptima independientemente del dispositivo que use. | 3 |
| US-11 | Conocer más a fondo los servicios que ofrecen | Como visitante interesado, quiero conocer de manera más específica los servicios que ofrecen por medio de capturas de pantallas, para comprender su solución y decidir si optar por ella. | 3 |
| US-12 | Ver planes de suscripción disponibles | Como visitante interesado, quiero ver una sección clara que me presente los planes de suscripción disponibles, separados por Planes para Técnicos y Planes para Propietarios, para comparar fácilmente sus características y precios. | 3 |
| US-18 | Validación de datos de registro | Como usuario, quiero recibir retroalimentación inmediata sobre la validez de los datos que ingresó durante el registro para corregir errores rápidamente. | 3 |
| US-23 | Visualización de Perfil de Propietario | Como propietario registrado, quiero visualizar mi perfil, para revisar mi información personal y preferencias almacenadas en el sistema. | 3 |
| US-30 | Configuración de Notificaciones Personalizadas | Como usuario de la plataforma, quiero configurar mis preferencias de notificaciones (email, SMS, push) y frecuencia, para recibir información relevante sin ser saturado de mensajes. | 3 |
| US-43 | Descripción Detallada del Problema Eléctrico | Como propietario que ya ha seleccionado un servicio, quiero añadir una descripción detallada de mi problema, para que el técnico asignado conozca el contexto específico antes de su llegada. | 3 |
| US-45 | Cancelación de servicios programados | Como cliente, quiero cancelar un servicio programado con anticipación para evitar cargos innecesarios. | 3 |
| US-47 | Historial de servicios contratados | Como cliente, quiero ver un historial de los servicios que he contratado anteriormente para referencia futura. | 3 |
| US-55 | Eliminar Servicios del Catálogo | Como técnico registrado, quiero eliminar servicios que ya no ofrezco de mi catálogo, para evitar que el sistema me asigne trabajos que no puedo realizar. | 3 |
| US-63 | Historial de Clientes Atendidos | Como Técnico, quiero acceder a un historial detallado de los clientes que he atendido, para dar seguimiento a relaciones profesionales y mejorar mi servicio basado en experiencias previas. | 3 |
| US-68 | Exportación de datos de consumo | Como usuario, quiero exportar mis datos históricos de consumo en formatos comunes (CSV, Excel) para análisis externos. | 3 |
| TS-01 | Registrar Propiedad | Como desarrollador, quiero crear un endpoint POST para registrar una propiedad asociada a un propietario. | 3 |
| TS-02 | Obtener Propiedades por Propietario | Como desarrollador, quiero crear un endpoint GET para listar todas las propiedades registradas por un propietario. | 3 |
| TS-04 | Actualizar Stock de Componente | Como desarrollador, quiero crear un endpoint PATCH para actualizar el stock de un componente del inventario del técnico. | 3 |
| TS-12 | Obtener Evaluaciones por Técnico | Como desarrollador, quiero crear un endpoint GET para obtener las evaluaciones de un técnico. | 3 |
| TS-22 | Endpoint de Gestión de Perfiles | Como desarrollador, necesito crear endpoints para visualizar y editar perfiles de usuario para soportar la funcionalidad de gestión de cuentas diferenciada por tipo de usuario. | 3 |
| TS-15 | Reinicio Mensual de Contador | Como desarrollador, quiero crear una tarea programada (cron job) que se ejecute mensualmente. | 3 |
| TS-19 | Verificación de Email | Como desarrollador, quiero crear endpoints para verificar emails de usuarios para completar el proceso de registro. | 3 |
| TS-21 | Recuperación de Contraseña | Como desarrollador, quiero crear endpoints para recuperación de contraseña para permitir a usuarios restablecer sus credenciales. | 3 |
| TS-22 | Endpoints de Gestión de Perfiles | Como desarrollador, quiero crear endpoints CRUD para gestión de perfiles para permitir a usuarios actualizar su información personal. | 3 |
| US-13 | Registro de cuentas como Dueño de Hogar | Como dueño de hogar, quiero registrarme para tener una cuenta en la aplicación, para gestionar los componentes eléctricos de mi vivienda. | 5 |
| US-14 | Registro de cuentas como Dueño de Empresa | Como dueño o representante de empresa, quiero registrarme para tener una cuenta en la aplicación, para gestionar los componentes eléctricos de mis instalaciones comerciales. | 5 |
| US-15 | Registro de cuentas para Técnicos | Como Técnico de componentes eléctricos yo servicios, quiero registrarme para tener una cuenta en la aplicación, para ofrecer mis productos y servicios a los usuarios. | 5 |
| US-16 | Verificación de cuenta por correo electrónico | Como usuario, quiero verificar mi cuenta a través de un enlace enviado por correo electrónico para confirmar mi identidad. | 5 |
| US-17 | Inicio de sesión de usuarios | Como usuario registrado, quiero iniciar sesión en la aplicación con mis credenciales para acceder a mi cuenta y utilizar las funcionalidades de la plataforma. | 5 |
| US-21 | Recuperación de Contraseña | Como usuario registrado, quiero recuperar mi contraseña en caso de olvidarla, para volver a acceder a mi cuenta de manera segura. | 5 |
| US-24 | Edición de Perfil de Propietario | Como propietario registrado, quiero editar mi información personal y preferencias, para mantener mi perfil actualizado y tener más control sobre este. | 5 |
| US-25 | Visualización de Perfil de Técnico | Como Técnico registrado Quiero visualizar mi perfil profesional Para revisar cómo se presenta mi información y servicios a los clientes potenciales. | 5 |
| US-27 | Entrar a un dashboard Personalizado | Como usuario de la plataforma, quiero acceder a un dashboard personalizado al iniciar sesión, para visualizar de forma inmediata la información relevante según mi rol y actividad reciente. | 5 |
| US-28 | Crear Portafolio Digital con Evidencias de Trabajo | Como Técnico de servicios eléctricos, quiero crear un portafolio digital dentro de mi perfil que incluya fotos, descripciones y referencias de trabajos anteriores, para mostrar mi experiencia y generar mayor confianza en potenciales clientes. | 5 |
| US-29 | Configuración de Zona de Cobertura Geográfica | Como técnico registrado, quiero configurar mi zona de cobertura geográfica especificando radio de acción y ubicaciones donde ofrezco servicios, para recibir solicitudes solo de clientes dentro de mi área de trabajo. | 5 |
| US-31 | Crear Componente Eléctrico | Como técnico Quiero registrar nuevos componentes eléctricos en mi inventario Para mantener un inventario completo de mi infraestructura eléctrica. | 5 |
| US-32 | Editar Componente Eléctrico | Como técnico Quiero modificar la información de los componentes eléctricos registrados Para mantener actualizada la información técnica y de consumo. | 5 |
| US-33 | Eliminar Componente Eléctrico | Como técnico Quiero eliminar componentes eléctricos de mi inventario Para mantener actualizada mi configuración cuando retire o reemplace equipos. | 5 |
| US-34 | Registro de Propiedad (Propietario) | Como propietario, quiero registrar una nueva propiedad en el sistema, incluyendo su dirección y geolocalización, para solicitar servicios para ella. | 5 |
| US-35 | Edición de Información de Propiedad (Propietario) | Como propietario, quiero editar la información de mis propiedades registradas (ej. dirección, características), para mantenerla actualizada. | 5 |
| US-36 | Eliminación de Propiedad (Propietario) | Como propietario, quiero eliminar una propiedad de mi cuenta, si ya no la gestiono. | 5 |
| US-37 | Registro de Inventario de Componentes (Técnico) | Como Técnico, quiero registrar los componentes eléctricos que tengo en mi inventario, incluyendo cantidad y costo, para controlar mi stock. | 5 |
| US-38 | Actualización de Stock de Componentes (Técnico) | Como Técnico, quiero actualizar las cantidades de mis componentes en inventario después de una compra o uso en un servicio, para mantener la precisión del stock. | 5 |
| US-39 | Configuración de Alertas de Stock Mínimo (Técnico) | Como Técnico, quiero definir umbrales de stock mínimo para mis componentes y recibir alertas cuando el stock alcance ese nivel, para planificar reposiciones. | 5 |
| US-40 | Contratación de Servicios Eléctricos mediante Wizard | Como propietario de PyME, quiero contar con un proceso guiado paso a paso para contratar servicios eléctricos, para solucionar mis problemas de forma rápida y sin complicaciones. | 5 |
| US-41 | Selección de Propiedad | Como propietario con múltiples propiedades, quiero seleccionar la propiedad específica donde necesito el servicio, para que el sistema asigne al técnico más cercano a esa ubicación. | 5 |
| US-42 | Carga Manual de Datos de Recibos Eléctricos (3-6 recibos) | Como propietario solicitando un servicio, quiero ingresar manualmente los datos clave de mi último recibo eléctrico durante el proceso de solicitud, para registrar mi historial de consumo y permitir análisis a largo plazo en mi panel de Analytics. | 5 |
| US-44 | Selección de Servicio Específico del Catálogo | Como propietario, después de seleccionar mi propiedad, quiero ver una lista de servicios específicos disponibles en mi zona (ej 'Instalación de tomacorriente', 'Diagnóstico General') y seleccionar el que necesito, para que el sistema sepa exactamente qué trabajo solicitar y pueda automatizar la asignación. | 5 |
| US-46 | Notificación de Asignación Automática de Técnico (Propietario) | Como propietario, después de que mi solicitud de servicio es asignada automáticamente, quiero recibir una notificación con la información del técnico asignado. | 5 |
| US-48 | Configurar Horarios de Trabajo Semanales | Como técnico registrado, quiero configurar mis horarios de trabajo por día de la semana (ej Lunes 8AM-6PM, Martes 10AM-4PM) y definir la duración promedio que me toma cada tipo de servicio, para que el sistema pueda asignarme automáticamente trabajos solo en mis horarios laborales disponibles. | 5 |
| US-49 | Modificar Horarios de Trabajo Existentes | Como técnico registrado, quiero modificar mis horarios de trabajo ya configurados (cambiar horas de inicio/fin, días laborales), para ajustar mi disponibilidad según cambios en mi situación personal o comercial. | 5 |
| US-50 | Bloquer Fechas y Horarios Específicos | Como técnico registrado, quiero bloquear fechas específicas (vacaciones, emergencias) o horarios puntuales (citas médicas, otros compromisos) en mi calendario, para evitar que el sistema me asigne trabajos durante esos períodos. | 5 |
| US-51 | Visualizar Agenda de Trabajos Asignados Automáticamente | Como técnico registrado, quiero visualizar en un calendario todos los trabajos que el sistema me ha asignado automáticamente dentro de mis horarios disponibles, para planificar mi día y ver mi carga de trabajo semanal. | 5 |
| US-52 | Configurar Tiempo de Traslado Entre Servicios | Como técnico registrado, quiero configurar el tiempo promedio que necesito para trasladarme entre ubicaciones en mi zona de cobertura, para que el sistema considere estos intervalos al asignarme trabajos consecutivos. | 5 |
| US-54 | Modificar Servicios y sus Recetas de Componentes | Como técnico registrado, quiero modificar los servicios existentes en mi catálogo (precio, descripción, componentes necesarios), para mantener actualizada mi oferta y las recetas de materiales. | 5 |
| US-56 | Establecimiento Precios por Tipo de Servicio y Zona | Como técnico registrado, quiero establecer precios diferenciados por tipo de servicio y opcionalmente por zona dentro de mi área de cobertura, para tener una estructura tarifaria clara y rentable. | 5 |
| US-57 | Beneficio de Solicitud Prioritaria | Como propietario con suscripción Premium, al crear una solicitud de servicio, quiero tener disponible y activar la opción de marcar como prioritaria, para que mi solicitud tenga preferencia en el sistema de asignación y así resolver mi problema más rápidamente. | 5 |
| US-58 | Notificación de Límite de Solicitudes Alcanzado | Como propietario del plan Básico, al intentar crear una solicitud que excede mi límite mensual (2), quiero ser notificado claramente por el sistema y ver una opción directa para mejorar mi plan a Premium, para entender las reglas del plan gratuito y continuar usando el servicio si lo necesito. | 5 |
| US-59 | Seguimiento de Estados de Servicio en Tiempo Real | Como propietario y técnico, quiero ver el estado actual del servicio (programado, confirmado, en progreso, completado) actualizado en tiempo real, para estar informado sobre el progreso del trabajo. | 5 |
| US-60 | Registro Fotográfico de Trabajos (Antes/Después) | Como técnico ejecutando un servicio, quiero tomar y subir fotografías del área de trabajo antes y después de la intervención, para documentar el trabajo realizado y protegerme ante reclamos. | 5 |
| US-61 | Generación de Reportes Técnicos Estructurados | Como técnico completando un servicio, quiero generar un reporte técnico estructurado que incluya los componentes utilizados de la 'receta' original, los procedimientos realizados y recomendaciones, para profesionalizar mi servicio y dejar constancia del trabajo. | 5 |
| US-62 | Actualización Automática de Inventario Post-Servicio | Como técnico que completa un servicio, quiero que el sistema descuente automáticamente del mi inventario los componentes que marqué como utilizados en el reporte técnico, para mantener mi stock actualizado sin trabajo manual. | 5 |
| US-64 | Sistema de Calificación Post-Servicio | Como usuario, quiero calificar y dejar reseñas sobre los servicios que he utilizado, para compartir mi experiencia con otros usuarios y proporcionar retroalimentación a los Técnicos. | 5 |
| US-65 | Visualización de Calificaciones y Reseñas | Como usuario, quiero ver las calificaciones y reseñas dejadas por otros usuarios, para tomar decisiones informadas sobre qué servicios utilizar. | 5 |
| US-66 | Retroalimentación directa de servicios | Como Técnico, quiero recibir retroalimentación directa sobre mis servicios para mejorar mi oferta. | 5 |
| TS-03 | Crear Componente | Como desarrollador, quiero crear un endpoint POST para que el técnico registre un nuevo componente en su inventario. | 5 |
| TS-05 | Crear Servicio de Técnico | Como desarrollador, quiero crear un endpoint POST para que el técnico defina un nuevo servicio en su catálogo, incluyendo su receta de componentes. | 5 |
| TS-06 | Obtener Servicios por Zona | Como desarrollador, quiero crear un endpoint GET que devuelva los servicios disponibles en una zona geográfica específica. | 5 |
| TS-08 | Enviar Solicitud de Servicio | Como desarrollador, quiero crear un endpoint POST que registre los detalles de una solicitud de servicio. | 5 |
| TS-10 | Actualización Automática de Stock | Como desarrollador, quiero crear un listener que reaccione al evento Servicio Completado para descontar el stock. | 5 |
| TS-11 | Enviar Evaluación de Servicio | Como desarrollador, quiero crear un endpoint POST para registrar una evaluación. | 5 |
| TS-16 | Sesión de Portal de Stripe | Como desarrollador, quiero crear un endpoint que genere una sesión para el Portal de Cliente de Stripe. | 5 |
| TS-17 | Endpoint de Autenticación JWT | Como desarrollador, quiero crear un endpoint de login que genere tokens JWT para permitir la autenticación segura de usuarios. | 5 |
| TS-18 | Endpoint de Registro de Usuarios | Como desarrollador, quiero crear endpoints de registro diferenciados para permitir el registro de propietarios y técnicos. | 5 |
| TS-20 | Middleware de Autorización | Como desarrollador, quiero crear middleware de autorización para controlar acceso a endpoints según roles de usuario. | 5 |
| TS-23 | Sistema de Notificaciones Básico | Como desarrollador, quiero crear un servicio básico de notificaciones para enviar emails simples a los usuarios. | 5 |
| US-26 | Edición de Perfil de Técnico | Como Técnico registrado, quiero editar mi información profesional, certificaciones y servicios ofrecidos para mantener mi perfil actualizado y atractivo para los clientes. | 8 |
| US-53 | Crear Servicios en Catálogo con Recetas de Componentes | Como técnico registrado, quiero crear nuevos servicios en mi catálogo especificando qué componentes eléctricos exactos necesito y en qué cantidades (receta), para que el sistema verifique automáticamente si tengo stock suficiente antes de asignarme ese tipo de trabajo. | 8 |
| TS-07 | Iniciar Flujo de Solicitud | Como desarrollador, quiero crear un endpoint que valide el plan del propietario al iniciar una solicitud. | 8 |
| TS-09 | Asignar Técnico Automáticamente | Como desarrollador, quiero implementar la lógica para asignar automáticamente un técnico a una solicitud. | 8 |
| TS-13 | Conectar a Base de Datos | Como desarrollador, quiero configurar la conexión a la base de datos PostgreSQL. | 8 |
| TS-14 | Listener de Webhook de Stripe | Como desarrollador, quiero crear un endpoint para recibir y procesar webhooks de Stripe. | 8 |

<div style="page-break-after: always;"></div>

## Capítulo IV: Product Design

Este capítulo detalla el diseño de la solución propuesta desde una perspectiva técnica y visual. Incluye la arquitectura de software bajo principios de Domain-Driven Design (DDD), la selección de tecnologías, el diseño de base de datos y el modelado de entidades. También se presentan los mockups, diagramas de flujo y lineamientos de experiencia de usuario.
 
### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

**Branding:**

El logo de ElectroLink representa la esencia de la plataforma como un puente moderno y confiable entre soluciones eléctricas y quienes las necesitan. El enchufe central simboliza el rubro eléctrico y la conexión energética, mientras que el contorno en forma de techo alude a hogares y oficinas, principales escenarios donde se brindan los servicios. Las líneas internas sugieren flujo de energía y conectividad digital, reforzando el enfoque tecnológico. La paleta de colores —azul eléctrico, blanco y naranja— transmite confianza, claridad e innovación. Todo esto, junto con una tipografía limpia y moderna, refuerza la identidad de ElectroLink como una herramienta accesible, profesional y orientada a resolver problemas reales.

**Variantes de Logo:**

*Logo Original*

<img src="https://i.postimg.cc/MGm57smQ/434232.png"/>

*Logo sin Letras*

<img src="https://i.postimg.cc/Nf2xJGxY/423423.png"/>

*Colores Invertidos*

<img src="https://i.postimg.cc/k5sN627N/766.png"/>

**Typography:**

La tipografía de nuestra marca tiene un estilo moderno y ordenado, va de la mano con la imagen de nuestra marca y lo que nosotros, como startup, queremos transmitir. Se usará un lenguaje casual y sencillo, con la finalidad de que el público se sienta cómodo usando nuestra plataforma.
La tipografía debe ser clara y legible, utilizando la fuente "Abel", que se mantendrá consistente en toda la plataforma. Los títulos y subtítulos usarán una fuente ligeramente más grande que el cuerpo del texto para mejorar la jerarquía visual. En general, se debe usar un tamaño que garantice que todo el texto sea fácilmente legible tanto en pantallas pequeñas como grandes.

**Colors:**

La paleta de colores elegida para la web de ElectroLink fue diseñada para complementar visualmente el logo sin competir con él, manteniendo una identidad coherente, moderna y profesional. El azul grisáceo suave establece una base limpia y tecnológica, ideal para fondos que no cansan la vista y dan protagonismo al contenido. Este tono, junto al celeste claro para botones o elementos interactivos, mantiene la sensación de confianza y dinamismo que el logo transmite, pero con una suavidad que hace la interfaz más amigable.
Por otro lado, el gris cálido y el grafito profundo aportan equilibrio visual y legibilidad. Son tonos sobrios que ayudan a jerarquizar la información sin recargarla, perfectos para textos y detalles estructurales. El naranja pastel, inspirado en el logo pero más atenuado, actúa como acento para destacar avisos o llamadas a la acción sin ser intrusivo. Finalmente, el verde menta claro introduce un toque de frescura y vitalidad, ideal para confirmar acciones exitosas o transmitir sensación de progreso. En conjunto, esta paleta respalda los valores de la marca: precisión, accesibilidad, tecnología y conexión humana.

## Paleta de Colores – ElectroLink

| Color                | Uso                                              | Código Hex              |
|----------------------|--------------------------------------------------|--------------------------|
| Azul grisáceo suave  | Fondo de secciones, tarjetas, menús laterales    | `#B5D5F5`, `#E8EEF7`     |
| Gris cálido          | Texto secundario, bordes suaves, fondos suaves   | `#A9B1BA`                |
| Celeste claro        | Hover, botones secundarios, íconos de ayuda      | `#B5D5F5`, `#3DADFF`     |
| Amarillo pastel      | Elementos destacados suaves, fondos de aviso     | `#FFE492`, `#D5D6D8`     |
| Grafito profundo     | Texto principal, íconos oscuros                  | `#2E3A59`                |

<hr>

#### 4.1.2. Web Style Guidelines

De manera que el contenido de nuestro sitio web se vea organizado y sea mostrado de manera adecuada, implementamos el patrón F. El objetivo del patrón F en un sitio web es reflejar la forma natural en la que los usuarios escanean el contenido, empezando por la parte superior izquierda y moviéndose en forma de "F" hacia abajo. Este diseño resalta la información clave en las primeras líneas y en el lateral izquierdo, donde la vista se concentra más. Mejora la usabilidad al alinear la estructura con el comportamiento visual del usuario, facilitando la lectura rápida y efectiva. Se utiliza para mejorar la experiencia del usuario y destacar contenido relevante.

<img src="https://i.postimg.cc/JzWFVYKs/6456456.png"/>

## 4.2. Information Architecture

La arquitectura de información que se implementará en ElectroLink está diseñada para facilitar una experiencia de navegación clara, eficiente y centrada en conectar usuarios con proveedores de servicios y componentes eléctricos. Desde el menú principal, los visitantes podrán acceder rápidamente a categorías clave como "Proveedores", "Servicios", "Asesoramiento", y "Mantenimientos preventivos", lo que les permitirá encontrar con facilidad las soluciones que se ajusten a sus necesidades técnicas o del hogar.
La plataforma contará con un sistema de filtrado inteligente que permitirá a los usuarios buscar proveedores según ubicación, especialización (instalaciones, mantenimiento, venta de componentes), certificaciones legales y valoraciones de otros clientes. Además, ElectroLink ofrecerá un apartado de asesoría técnica, donde los usuarios podrán consultar artículos, guías rápidas y recomendaciones para la gestión segura de instalaciones eléctricas tanto en hogares como en negocios.
Asimismo, cada proveedor tendrá un perfil verificado con información detallada sobre sus servicios, casos anteriores, contacto directo y una sección de opiniones. También se incluirá un sistema de solicitud rápida de cotización, permitiendo a los clientes establecer una comunicación ágil y efectiva. Con esta arquitectura, ElectroLink busca no solo ordenar y categorizar la información de manera accesible, sino también fomentar la confianza, la transparencia y una red de colaboración técnica eficiente, alineada con estándares de seguridad y legalidad en el rubro eléctrico.

#### 4.2.1. Organization Systems
Para representar la estructura de los usuario se han realizado diagramas para la explicación de la funcionalidades de la aplicación y el recorrido del usuario en la misma.
<img src="https://i.postimg.cc/W3D8J0XR/57567.png"/>

#### 4.2.2. Labeling Systems

| Sección                                     | Etiqueta                        | Descripción                                                                 |
|--------------------------------------------|----------------------------------|-----------------------------------------------------------------------------|
| **Menú de inicio**                          | Inicio                           | Página principal con visión general de la plataforma y acceso rápido a secciones. |
|                                             | Cómo funciona                    | Explicación clara y visual del funcionamiento del sistema paso a paso.     |
|                                             | Testimonios                      | Opiniones y experiencias reales de usuarios satisfechos.                   |
|                                             | Contacto                         | Formulario y canales disponibles para consultas, soporte o sugerencias.    |
|                                             |                                  |                                                                            |
| **Botones de ingreso y salida               | Iniciar Sesión                   | Botón donde los usuarios podrán iniciar sesión con su cuenta.              |
|   de la plataforma**                        | Iniciar Sesión con Google        | Botón que permite a los usuarios iniciar sesión con su cuenta de Google.   |
|                                             | Iniciar Sesión con Facebook      | Botón que permite a los usuarios iniciar sesión con su cuenta de Facebook. |
|                                             | Registrarse                      | Botón donde los usuarios podrán crearse una cuenta en la plataforma.       |
|                                             | Dashboard                        | Botón que dirige a la interfaz del usuario seleccionado.                   |
|                                             | Cerrar Sesión                    | Botón que permite al usuario empezar una conversación con el asistente virtual. |
|                                             |                                  |                                                                            |
| **Sección menú del propietario**            | Historial de servicios           | Visualiza el registro de mantenimientos y reparaciones realizadas.         |
|                                             | Inventario de electrodomésticos  | Consulta la lista de equipos registrados y su consumo energético.          |
|                                             | Buscar proveedores               | Encuentra técnicos y proveedores certificados.                             |
|                                             | Detectar problema                | Analiza factores para identificar fallas o excesos de consumo.             |
|                                             | Monitorear energía               | Seguimiento del consumo eléctrico mensual y estado de componentes.         |
|                                             | Inventario de electrodomésticos (Subir) | Añade nuevos dispositivos con sus características de consumo.       |
|                                             | Suscripción                      | Gestión del plan actual y beneficios exclusivos.                           |
|                                             | Mi perfil                        | Edición de información personal, preferencias y datos de contacto.         |
|                                             |                                  |                                                                            |
| **Menú de proveedores y técnicos**          | Gestión y Agenda de Citas        | Organiza, programa y visualiza citas con clientes.                         |
|                                             | Gestión de Servicios Ofrecidos   | Administra los servicios disponibles y sus detalles.                       |
|                                             | Historial de Servicios           | Registro completo de todos los servicios realizados.                       |
|                                             | Panel de Métricas y Rendimiento  | Estadísticas clave sobre actividad y eficiencia del proveedor.             |
|                                             | Inventario y Catálogo de Productos (En caso aplique) | Gestiona stock y presenta productos disponibles.       |
|                                             | Subscripción                     | Visualiza y gestiona el plan de suscripción y beneficios.                  |
|                                             | Mi Perfil                        | Edita y actualiza la información personal y profesional.                   |

<hr>

### 4.2.3. SEO Tags and Meta Tags

**Landing Page Title:** ElectroLink - Tu conexión segura a la electricidad

**Description:** ElectroLink es una plataforma enfocada en conectar a proveedores de componentes o servicios eléctricos con clientes que necesitan asesoramiento o asistencia para realizar mantenimientos preventivos en sus hogares u oficinas.

**Meta Keywords:** seguridad, ahorro eléctrico, mantenimiento, asesoramiento.

**ElectroLink Meta Author:** ElectroLink

**Meta Description:** facilitar la conexión entre clientes que necesitan servicios eléctricos confiables y proveedores calificados.

**Title:** ElectroLink

**Description:** Buscar conectar a dueños de hogares urbanos con proveedores técnicos eléctricos certificados, garantizando servicios seguros y eficientes dentro de los parámetros legales mediante una plataforma intuitiva y fácil de usar.

**Meta Keywords:** seguridad, ahorro eléctrico, mantenimiento, asesoramiento.

**Meta Author:** ElectroLink

<hr>

### 4.2.4. Searching Systems

ElectroLink cuenta con un sistema de búsqueda avanzada que permite a los usuarios encontrar servicios y productos eléctricos de forma eficiente, a través de múltiples filtros:

| **Filtro**                         | **Descripción**                                                                                                                                          |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Tipo de Servicio**              | Permite al usuario buscar proveedores en función del tipo de servicio requerido (instalación, mantenimiento preventivo, reparación, auditoría eléctrica, etc.). |
| **Ubicación / Zona**              | Filtro geográfico que ayuda a encontrar proveedores o técnicos disponibles en una zona específica o cercana al domicilio/oficina del usuario.              |
| **Disponibilidad de Agenda**      | Permite filtrar proveedores según fechas y horarios disponibles para programar una cita.                                                                 |
| **Certificación del Proveedor**   | Muestra solo técnicos o empresas que cuentan con certificaciones válidas y actualizadas en el área eléctrica.                                             |
| **Rango de Precio**               | Filtra servicios o productos según el presupuesto disponible del usuario, desde opciones económicas hasta servicios premium.                             |
| **Proveedores con Mejores Reseñas** | Filtro para mostrar técnicos con mayores calificaciones o comentarios positivos según otros usuarios.                                                   |
| **Categoría de Producto Eléctrico** | Ayuda a encontrar productos específicos en el inventario (bombillas, disyuntores, medidores, enchufes, etc.).                                           |
| **Historial de Consumo Energético** | Permite visualizar patrones de consumo eléctrico mensual o anual filtrando por fecha o dispositivos.                                                   |
| **Planes de Suscripción**         | Filtra y compara distintos planes de suscripción según los beneficios ofrecidos (monitoreo, asesoría, prioridad en atención, etc.).                       |


### 4.2.5. Navigation Systems

Los sistemas de navegación de ElectroLink han sido diseñados para guiar de forma intuitiva a los usuarios a través del Landing Page y la aplicación, facilitando la exploración del contenido y el acceso a las funcionalidades clave. La estructura sigue una lógica clara que permite a cada tipo de usuario (hogar, oficina, proveedor) encontrar rápidamente lo que necesita mediante menús jerárquicos, enlaces destacados y botones de acción visibles.

<img src="https://i.postimg.cc/LXBXDbyj/78768.png"/>

### 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe.

<img src="https://i.postimg.cc/wx2MsnRp/67867.png"/>

<img src="https://i.postimg.cc/kXh5T8yY/32432.png"/>

<img src="https://i.postimg.cc/Y9k2vxp0/5675.png"/>

### 4.3.2. Landing Page Mock-up

<img src="https://i.postimg.cc/7PKPL7jP/5675.png"/>

<img src="https://i.postimg.cc/fTwVkDHZ/75675.png"/>

### 4.4. Mobile Applications UX/UI Design.

### 4.4.1. Mobile Applications Wireframes.

### 4.4.2. Mobile Applications Wireflow Diagrams

### 4.4.3. Mobile Applications Mock-ups

### 4.4.4. Mobile Applications User Flow Diagrams

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping.
### 4.5.2. iOS Mobile Applications Prototyping.

## 4.6. Web Applications UX/UI Design.

### 4.6.1. Web Applications Wireframes.

## Web Applications Wireframes - ElectroLink

En esta sección se presentan los **wireframes de la aplicación web de ElectroLink**, los cuales permiten visualizar cómo será la estructura y disposición de los elementos en la interfaz. Estos bocetos funcionales aseguran una experiencia fluida, clara e inclusiva para los diferentes segmentos de usuarios, como propietarios de hogares, pequeños empresarios y proveedores técnicos, incluyendo además personas con ansiedad social, TEA, o discapacidades físicas.

El propósito de los wireframes es establecer la **estructura base de la aplicación**, mostrando la organización de la información, la navegación y la ubicación de los elementos interactivos sin enfocarse aún en los aspectos visuales finales. Esta etapa es crucial para garantizar una **experiencia de usuario intuitiva y accesible desde el inicio del diseño**.

---

### Elementos clave del diseño

#### Arquitectura de la información

- El contenido y las funciones están organizadas para facilitar el acceso a herramientas como el historial de servicios, monitoreo de consumo energético, o gestión de citas.
- Los wireframes incluyen pantallas clave como:
  - Panel de control del propietario.
  - Dashboard del proveedor técnico.
  - Formulario para solicitar mantenimientos preventivos.
  - Historial de dispositivos y consumo energético.
- Se ha priorizado una **navegación simple y accesible**, permitiendo que usuarios con diversas habilidades puedan moverse con facilidad por la plataforma.

#### Estructura de la interfaz

- Los elementos interactivos (botones, menús, tarjetas de información) están ubicados estratégicamente para que el usuario pueda realizar tareas con pocos clics.
- Las pantallas permiten acceso directo a secciones importantes como:
  - Subir o editar dispositivos eléctricos.
  - Contactar proveedores certificados.
  - Visualizar métricas de rendimiento o consumo.
- Se incluye también una sección de perfil adaptable y configurable, especialmente útil para personas que requieren adaptaciones visuales, físicas o cognitivas.

---

### Principios de diseño aplicados

- **Simplicidad**: Cada interfaz está diseñada para minimizar la carga cognitiva, con estructuras limpias que priorizan las acciones más importantes para el usuario.
- **Consistencia**: Todos los botones, iconos y menús siguen un mismo estilo visual y funcional, lo que reduce el tiempo de aprendizaje para los usuarios.
- **Accesibilidad**: Se aplican principios de diseño inclusivo, incluyendo opciones como:
  - Ajuste del tamaño de texto y botones.
  - Contraste de colores adecuado.
  - Navegación compatible con teclado y lectores de pantalla.
  - Diseño responsive para su uso en laptops, tablets y móviles.

---
Los wireframes son una guía esencial para la implementación efectiva de la plataforma ElectroLink, alineando las necesidades de los usuarios con un diseño funcional, ordenado y accesible para todos.

<img src="https://i.postimg.cc/wM7CMts3/75675.png"/>

<img src="https://i.postimg.cc/T38z232Y/686.png"/>

<img src="https://i.postimg.cc/G2SfWcSR/3121231.png"/>

<img src="https://i.postimg.cc/1XkjzvQY/6757.png"/>

<img src="https://i.postimg.cc/c1v1r6WQ/3565.png"/>

<img src="https://i.postimg.cc/fW1zXZW1/67456.png"/>

<img src="https://i.postimg.cc/x129xRzR/453535.png"/>

### 4.6.2. Web Applications Wireflow Diagrams

<img src="https://i.postimg.cc/xTw4P2L5/imagen-2025-07-08-211031407.png"/>

<img src="https://i.postimg.cc/J0BQysYL/imagen-2025-07-08-211104504.png"/>

<img src="https://i.postimg.cc/SKP55SPh/4243.png"/>

<img src="https://i.postimg.cc/g0xtv92B/4534534.png"/>
<br>

[Abrir diagrama en Lucidchart](https://lucid.app/lucidchart/9bc93c27-6140-47f1-9cfc-e7c0c5a15134/edit?invitationId=inv_f9a0cb75-977e-4669-a09e-21a42409c64d&page=0_0)

### 4.6.3. Web Applications Mock-ups

<img src="https://i.postimg.cc/G2YM5kYF/4645645.png"/>

<img src="https://i.postimg.cc/jdvMmqWF/6456456.png"/>

<img src="https://i.postimg.cc/7ZWmPBn1/6456457.png"/>

<img src="https://i.postimg.cc/dtQB2MWm/8678.png"/>

<img src="https://i.postimg.cc/Sx3fbnmD/88888.png"/>

<img src="https://i.postimg.cc/8cphmWbP/56756756.png"/>

<img src="https://i.postimg.cc/PJS13x6b/78768768.png"/>

### 4.6.4. Web Applications User Flow Diagrams

En esta sección, el equipo define el web appication user flow diagram
<img src="https://i.postimg.cc/26wcTDgQ/image-37.png"/>

## 4.7. Web Applications Prototyping

Esta sección presenta los prototipos de interfaz de usuario , los cuales incluyen simulaciones de interacción y navegación. Las decisiones de
interacción se fundamentan en criterios clave, como la facilidad de uso, la accesibilidad y la optimización para distintos dispositivos.

<img src="https://i.postimg.cc/3Jw6Sk8d/image-36.png"/>


[Ver diseño en Figma](https://www.figma.com/design/sU4hpNItE2lZ88WrlTUKwy/Untitled?node-id=31-624&t=9AhvJafsRNaQO2cX-1)

## 4.8. Domain-Driven Software Architecture


### 4.8.1. Software Architecture Context Diagrams
En esta sección, el equipo incluye los diagramas de contexto
<br>
<img src="https://imgur.com/6gbMyIf.jpeg"/>


### 4.8.2. Software Architecture Container Diagrams
En esta sección, el equipo incluye los diagramas de contenedores

<br>

<img src="https://imgur.com/ZZDW5y4.jpeg"/>


### 4.8.3. Software Architecture Components Diagrams

En esta sección, el equipo incluye los diagramas de componentes

Authentication Bounded Context Diagram
<img src="https://imgur.com/YNbXMVY.jpeg" />

Profile Management Bounded Context Diagram
<img src="https://imgur.com/DHEUMxc.jpeg"/>

Invoice Monitoring Bounded Context Diagram
<img src="https://imgur.com/qQiuMvP.jpeg" />

Service Management Bounded Context Diagram
<img src="https://imgur.com/ZFMpv6y.jpeg" />

Service Contracting Bounded Context Diagram
<img src="https://imgur.com/rkgoUoA.jpeg" />

Subscription Billing Bounded Context Diagram
<img src="https://imgur.com/OsW1q22.jpeg" />

<hr>

### 4.9. Software Object-Oriented Design
<hr>

<hr>

#### 4.9.1. Class Diagrams
<hr>

[![image.png](https://i.postimg.cc/k4S8S4tS/image.png)](https://postimg.cc/sQVvd3mf)
<hr>

#### 4.9.2. Class Dictionary


| Clase | Atributo | Descripción | Tipo de dato |
| :---- | :---- | :---- | :---- |
| User | \-userID | id del usuario |  int |
| User | \-email | email del usuario | String |
| User | \-password | contraseña del usuario | String |
| User | \-phoneNumber | teléfono del usuario | String |
| User | \-firstName | nombre del usuario | String |
| User | \-lastName | apellido del usuario | String |
| User | \-registrationDate | fecha del registro del usuario | DateTime |
| User | \-isVerified | verificación de registro | Boolean |
| User | \-type | tipo de usuario | UserType |
| Provider | \-companyName | nombre de la compañia del proveedor | String |
| Provider | \-taxID | número de identificación fiscal | String |
| Provider | \-businessLicense | licencia de trabajo del proveedor | String |
| Provider | \-certifications | certificaciones del proveedor | List\<Certification\> |
| Provider | \-servicesOffered | servicios ofrecidos | List\<Service\>  |
| Provider | \-availabilitySchedule | horario de disponibilidad | List\<Availability\>  |
| Provider | \-isVerified | verificación de los datos del proveedor | Boolean |
| Provider | \-averageRating | rating promedio del proveedor | Double |
| HomeOwner | \-address | dirección del dueño de hogar | String |
| HomeOwner | \-properties | propiedades del dueño de hogar | List\<Property\> |
| BusinessOwner | \-companyName | nombre de la compañía del dueño PYME | String |
| BusinessOwner |  \-taxID | número de identificación fiscal | String |
| BusinessOwner | \-companyAddress | dirección de la compañía | String |
| BusinessOwner | \-BusinessProperties | propiedades de la compañía | List\<Property\> |
| Administrator | \-adminLevel | nivel de administrador | String |
| Report | \-reportID | id del reporte | int |
| Report | \-reporterID | id del reportante | int |
| Report | \-reportedID | id del reportado | int |
| Report | \-description | descripción del reporte | String |
| Report | \-reportDate | fecha del reporte | DateTime |
| Report | \-evidenceAttachments | evidencias del reporte | List\<String\> |
| Report | \-status | estado del reporte | ReportStatus |
| Report | \-ReportType | tipo del reporte |  ReportType |
| Property | \-propertyID | id de la propiedad | int |
| Property | \-address | dirección de la propiedad | String |
| Property | \-type | tipo de la propiedad | PropertyType  |
| Property | \-squareFootage | el área de la propiedad | int |
| Property | \-components | componentes electricos de la propiedad | List\<ElectricalComponent\> |
| ServiceRequest | \-requestID | id de la solicitud del servicio | int |
| ServiceRequest | \-userID | id del usuario | int |
| ServiceRequest | \-propertyID | id de la propiedad | int |
| ServiceRequest | \-serviceID | id del servicio | int |
| ServiceRequest | \-description | descripción de la solicitud del servicio | String |
| ServiceRequest | \-requestDate | fecha de la solicitud | DateTime |
| ServiceRequest | \-priority | nivel de prioridad de la solicitud | ServicePriority |
| ServiceRequest |  \-status | estado de la solicitud | ServiceRequestStatus |
| Invoice | \-invoiceID | id de la factura | int |
| Invoice | \-bookingID | id de la reserva | int |
| Invoice | \-invoiceNumber | número de la factura | String |
| Invoice | \-issueDate | fecha de emisión | DateTime |
| Invoice |  \-dueDate | fecha de vencimiento | DateTime |
| Invoice |  \-subtotal | subtotal de la factura | double |
| Invoice | \-tax | impuestos cobrados | double |
| Invoice | \-total | total de la factura | double |
| Invoice | \-status | estado de la factura | InvoiceStatus |
| ElectricalComponent | \-componentID | id del componente | int |
| ElectricalComponent | \-name | nombre del componente | String |
| ElectricalComponent | \-model | model del componente | String |
| ElectricalComponent | \-manufacturer | fabricante del componente | String |
| ElectricalComponent |  \-installationDate | fecha de la instalación del componente | DateTime |
| ElectricalComponent | \-lastMaintenanceDate | ultima fecha de mantenimiento del componente | DateTime |
| ElectricalComponent | \-status | estado del componente | ComponentStatus |
| ServiceBooking | \-bookingID | id de la reserva | int |
| ServiceBooking | \-requestID | id de la solicitud | int |
| ServiceBooking |  \-providerID | id del proveedor | int |
| ServiceBooking | \-scheduledDate | fecha establecida para el servicio | DateTime |
| ServiceBooking | \-startTime | hora de inicio del servicio | Time |
| ServiceBooking | endTime | hora de finalización del servicio | Time |
| ServiceBooking | \-finalPrice | precio final del servicio | double |
| ServiceBooking | \-status | estado del servicio | BookingStatus |
| ServiceRecord | \-recordID | id del registro del servicio | int |
| ServiceRecord |  \-bookingID | id de la reserva | int |
| ServiceRecord | \-workDone | trabajo realizado | String |
| ServiceRecord |  \-partsReplaced | partes reemplazadas durante el servicio | List\<String\> |
| ServiceRecord | \-technicalNotes | notas técnicas del servicio  | String |
| ServiceRecord | \-recommendations | recomendaciones del proveedor | List\<String\> |
| ServiceRecord | \-completionDate | fecha de finalización del servicio | DateTime |
| ServiceRecord | \-finalCost | costo final del servicio | double |
| Review | \-reviewID | id de la reseña | int |
| Review |  \-userID | id del usuario | int |
| Review |  \-providerID | id del proveedor | int |
| Review |  \-bookingID | id de la reserva | int |
| Review | \-rating | calificación del servicio | int |
| Review | \-comment | comentarios realizados post-servicio | String |
| Review |  \-reviewDate | flecha del resumen | DateTime |
| Review |  \-photos | fotos realizadas durante el servicio | List\<String\> |
| Payment | \-paymentID | id del pago | int |
| Payment | \-bookingID | id de la reserva | int |
| Payment |  \-amount | monto del pago | double |
| Payment | \-paymentDate | fecha del pago | DateTime |
| Payment | \-method | método del pago | PaymentMethod |
| Payment | \-status | estado del pago | PaymentStatus |
| Payment | \-transactionReference | referencia de la transacción | String |
| Notification | \-notificationID | id de la notificación | int |
| Notification | \-userID | id del usuario | int |
| Notification | \-title | título de la notificación |  String  |
| Notification | \-message | mensaje de la notificación |  String  |
| Notification |  \-sentDate | fecha de envío de la notificación | DateTime |
| Notification | \-isRead | validación de lectura de la notificación | boolean |
| Notification | \-type | tipo de notificación | NotificationType |
| Certification | \-certificationID | id del certificado | int |
| Certification | \-name | nombre del certificado | String |
| Certification | \-issuingOrganization | organización emitora de la certificación | String |
| Certification | \-issueDate | fecha de emisión de la certificación | DateTime |
| Certification | \-expiryDate | fecha de vencimiento de la certificación | DateTime |
| Certification | \-verificationCode | código de verificación de la certificación | String |
| Availability | \-availabilityID | id de la disponibilidad | int |
| Availability | \-day | fecha de la disponibilidad | DayOfWeek |
| Availability |  \-startTime | hora de inicio | Time |
| Availability | \-endTime | hora de finalización | Time |
| Availability | \-isAvailable | verificación de disponibilidad | Boolean |
| Suscription | \-subscriptionID | id de la suscripción | int |
| Suscription |  \-providerID | id del proveedor | int |
|  Suscription |  \-plan | plan de suscripción | SubscriptionPlan  |
| Suscription | \-startDate | fecha de inicio de la suscripción | DateTime |
| Suscription |  \-endDate | fecha de fin de la suscripción | DateTime |
| Suscription | \-billingCycle | ciclo de facturación de la suscripción | PaymentFrequency |
| Suscription | \-autoRenew | verificación de auto recarga del pago | boolean |
| Service | \-serviceID | id del servicio | int |
| Service | \-name | nombre del servicio |  String |
| Service | \-description | descripción del servicio | String |
| Service |  \-basePrice | precio base del servicio | double |
| Service | \-estimatedDuration | duración estimada del servicio | int |
| Service | \-inclusions | lo que incluye el servicio |  List\<String\>  |
| Service | \-category | categoría del servicio | ServiceCategory |
| Widget | \-widgetID | id del widget | int |
| Widget | \-title | título del widget | String |
| Widget | \-type | tipo del widget | WidgetType |
| Widget | \-positionX | posición en x del widget | int |
| Widget | \-positionY | posición en y del widget | int |
| Widget | \-width | anchura del widget | int |
| Widget | \-height | altura del widget | int |
| Widget | \-configuration | configuración del widget | Map\<String, Object\> |
| Dashboard | \-userID | id del usuario | int |
| Dashboard | \-widgets | widgets del dashboard | List\<Widget\> |
| Dashboard |  \-type | tipo de dashboard | DashboardType |
| Favorite | \-favoriteID | id de favoritos | int |
| Favorite | \-userID | id del usuario | int |
| Favorite | \-providerID | id del proveedor | int |
| Favorite | \-addedDate | fecha de inclusión a favoritos | DateTime |
| SupportTicket | \-ticketID | id del ticket | int |
| SupportTicket | \-userID | id del usuario | int |
| SupportTicket |  \-subject | asunto del ticket | String |
| SupportTicket | \-description | descripción del ticket | String |
| SupportTicket | \-submissionDate | fecha de envío del ticket | DateTime |
| SupportTicket | \-priority | prioridad del ticket | TicketPriority |
| SupportTicket |  \-status | estado del ticket | TicketStatus |
| SupportTicket | \-conversation | conversación del soporte | List\<Message\> |
| Message | \-messageID | id del mensaje | int |
| Message |  \-senderID | id del mensajero | int |
| Message | \-receiverID | id del receptor | int |
| Message | \-content | contenido del mensaje | String |
| Message | \-sentDate | fecha de envío del mensaje | DateTime |
| Message | \-isRead | verificación de que ha sido leído | boolean |
| Message |  \-attachments | adjuntos del mensaje |  List\<String\> |
<hr>

<hr>

### 4.10. Database Design
<hr>

<hr>

#### 4.10.1. Database Diagram

<hr>

<img src="https://i.postimg.cc/zD9VSTXz/90.png"/>
<hr>

<div style="page-break-after: always;"></div>


## Capítulo V: Product Implementation

Se documenta el proceso de implementación progresiva del sistema mediante sprints. Se incluyen las decisiones técnicas clave, estrategias de control de versiones, convenciones de codificación y validación del producto con usuarios reales. Además, se abordan los procedimientos de despliegue, pruebas funcionales y ajustes realizados tras retroalimentación de validación.

## 5.1. Software Configuration Management

Aunque la falta de una gestión adecuada de la configuración del software puede generar desorden, confusión y versiones inconsistentes entre los miembros del equipo, implementar un control riguroso sobre el código fuente, los documentos de diseño y los activos digitales asegura que todos trabajen de manera coordinada y eficiente. Así, la colaboración entre desarrolladores se fortalece y se evitan errores derivados de trabajar con archivos desactualizados.

<hr>

### 5.1.1. Software Development Environment Configuration

**Project Management**

| Plataforma    | Descripción                                                                                                                                                                                                                                                                                           | Enlace                       |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
| Trello        | Esta plataforma de gestión de proyectos ofrece funcionalidades para el seguimiento detallado del progreso de cada tarea a lo largo de su ciclo de vida, además de permitir la designación clara de responsables para cada actividad dentro del equipo de trabajo.                                      | https://trello.com           |
| Uxpressia     | Herramienta en línea que ayuda en el proceso de mapeo.                                                                                                                                                                                                                                              | https://uxpressia.com/      |
| Canva         | Es una aplicación web de diseño y comunicación visual donde los usuarios pueden diseñar lo que deseen y publicarlo. Cuenta con diversos formatos y estilos de creación para todo tipo de trabajo.                                                                                                    | https://www.canva.com      |
| Vertabelo     | Fundamental para el diseño, la documentación y la gestión de bases de datos relacionales, ya que simplifica el proceso de modelado, fomenta la colaboración y ayuda a garantizar la calidad y la coherencia de la estructura de los datos.                                                        | https://vertabelo.com   |
| Lucidchart    | Sirve como un lienzo visual versátil para representar cualquier tipo de información estructurada o proceso, facilitando la comprensión, la comunicación y la colaboración entre equipos.                                                                                                                | https://www.lucidchart.com/ |
| C4 Model      | Sistema de notación visual para arquitectos de software y equipos de desarrollo que ayuda a describir la arquitectura de un sistema de software en diferentes niveles de abstracción.                                                                                                                    | https://c4model.com            |

**Product UX/UI Desing**

| Plataforma | Descripción                                                                                                                                                                                                                            | Link                                                    |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|
| Figma      | Herramienta para el diseño de productos digitales que fomenta la colaboración, agiliza el flujo de trabajo y permite crear experiencias de usuario efectivas y visualmente atractivas.                                                 | https://www.figma.com |

**Software Development**

| Plataforma           | Descripción                                                                                                                                                                                                                            | Link                                                |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| HTML                | Sirve para definir la estructura y el contenido de una página web.                                                                                                                                                                      | https://www.w3schools.com/html/default.asp                                      |
| CSS                 | Se encarga de la presentación visual y el estilo de la página web.                                                                                                                                                                       | https://www.w3schools.com/css/default.asp                                       |
| JS                  | Añade interactividad y dinamismo a la página web.                                                                                                                                                                                        | https://www.w3schools.com/js/default.asp                               |
| Visual Studio Code  | Entorno de desarrollo que facilita la escritura, edición, depuración y gestión de código para una amplia gama de lenguajes y proyectos.                                                                                                    | https://code.visualstudio.com          |

**Software Documentation**

| Plataforma | Descripción                                             | Link                                                              |
|------------|---------------------------------------------------------|-------------------------------------------------------------------|
| GitHub     | Gestión de la documentación en función a repositorios y organizaciones | https://github.com          |
| Markdown   | Formato base para la presentación y documentación del proyecto | https://markdown.es/                     |
<br>

### 5.1.2. Source Code Management

Link Landing Page: https://electrolink-diseno-de-experimentos.github.io/Landing-Page

Link WebServices: https://electrolinkv3.onrender.com/swagger-ui/index.html#

Link FrontEnd: https://electrolink-195e0.web.app

Definir convenciones de nomenclatura para ramas en Git mejora la organización del flujo de trabajo y facilita la colaboración entre desarrolladores. Siguiendo buenas prácticas como las de Git Flow o trunk-based development, se puede establecer una estructura ordenada y predecible.

- Además, utilizar un esquema de nombres predecible permite:

- Automatizar procesos (CI/CD).

- Identificar fácilmente el propósito y alcance de una rama.

GitFlow es un modelo de gestión de ramas en Git que facilita el manejo de proyectos grandes mediante la separación en ramas principales y de características. En nuestro proyecto, utilizamos las siguientes ramas:

* **Rama `main`:** Esta rama contiene el código en producción, incluyendo archivos CSS, imágenes, JavaScript y la página principal en HTML. Aseguramos que todo el contenido aquí esté en un estado estable y listo para ser desplegado.

* **Rama `gh-pages`:** Esta rama se utiliza para desplegar y mostrar una versión visualizable del proyecto en GitHub Pages, permitiendo que cualquier persona acceda a la página `index.html` en tiempo real.

Además, contamos con un repositorio separado que organiza nuestras tareas en epics, utilizando archivos `.feature` que describen los criterios de aceptación para cada funcionalidad. Esto nos ayuda a mantener un seguimiento claro del progreso del desarrollo.

Elegimos GitHub como nuestra plataforma de colaboración para facilitar el seguimiento del progreso, la gestión de cambios y la visualización de actualizaciones. Las actualizaciones al código se reflejan automáticamente en `gh-pages`, permitiendo que los interesados vean los avances en tiempo real.

**Convenciones:**

✔ Convenciones para ramas feature
Prefijo: `feature/`
Formato: `feature/nombre-corto-descriptivo`

Ejemplo:
`feature/login-ui`
`feature/pdf-export`
`feature/api-integration-usuarios`

✔ Convenciones para ramas release
Prefijo: `release/`
Formato: `release/x.y.z (donde x, y, z son número mayor, menor y de parche)`

Ejemplo:
`release/1.0.0`
`release/2.1.0`

✔ Convenciones para ramas hotfix
Prefijo: `hotfix/`
Formato: `hotfix/x.y.z-nombre-corto`

Ejemplo:
`hotfix/1.0.1-fix-login-error`
`hotfix/2.3.2-bug-carrito`

Repositorio principal: https://github.com/ElectroLink-Diseno-de-Experimentos

<br>

### 5.1.3. Source Code Style Guide & Conventions

Se nombrará las siguientes etiquetas que utilizamos para desarrollar nuestra solución

**HTML**

* `<!DOCTYPE html>` - Define el tipo de documento como HTML5.
* `<html>` - Raíz del documento HTML.
* `<head>` - Encabezado del documento, donde se incluyen metadatos.
* `<meta>` - Define metadatos sobre el documento (charset y viewport).
* `<title>` - Título del documento.
* `<link>` - Para enlaces de icono, hoja de estilos CSS y fuente externa.
* `<body>` - Cuerpo del documento, donde se encuentra el contenido visible.
* `<header>` - Encabezado de la página.
* `<div>` - Contenedor para el logo y otros elementos.
* `<img>` - Imagen del logo.
* `<nav>` - Contenedor para la navegación.
* `<ul>` - Lista no ordenada de enlaces de navegación.
* `<li>` - Elemento de lista para cada enlace de navegación.
* `<a>` - Enlaces de navegación.
* `<button>` - Botón para el modo de deuteranopia.
* `<section>` - Define secciones de contenido principal:
  * Sección principal: `<h1>`, `<p>`
  * Por Qué Interactiva: `<h2>`, `<span>`, `<div>`, `<h3>`, `<p>`
  * Valor Propuesto: `<h3>`, `<p>`, `<img>`
  * Presentamos a...: `<h2>`, `<h4>`, `<p>`, `<img>`
  * Servicios: `<h2>`, `<div>`, `<h4>`, `<p>`
  * Testimonios: `<h2>`, `<p>`, `<img>`
  * Cómo empezar: `<h2>`, `<h5>`, `<strong>`, `<p>`
  * Descargar: `<h2>`, `<h3>`, `<span>`, `<a>`, `<img>`
* `<footer>` - Pie de página.
* `<small>` - Texto de derechos reservados.
* `<script>` - Script JavaScript para funcionalidades.

**CSS**

* `width:` Representa el ancho de un elemento.
* `height:` Representa el alto de un elemento.
* `padding:` Representa el espacio con relleno entre el borde y el contenido.
* `font-family:` Representa el tipo de letra.
* `font-size:` Representa el tamaño de letra.
* `font-weight:` Representa el grueso o el peso de la letra.
* `font-style:` Representa el estilo de letra.
* `Text-align:` Representa la alineación del texto.
* `color:` Otorga color al elemento.
* `Background-color:` Otorga color del fondo del elemento.

<hr>

### Convenciones Estándares y Referencias de Estilo de Código

| Lenguaje | Estándar / Convención Adoptada | Objetivo |
| :--- | :--- | :--- |
| **JavaScript** | **[Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)** o **[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)**. _Se elegirá uno de los dos de forma definitiva al inicio de la fase de codificación._ | Garantizar el uso de características modernas de ES6+ y prácticas recomendadas para sintaxis, espaciado, uso de comillas y estructuras de control. |
| **TypeScript** | **[TypeScript Recommended Coding Practices](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html)** y alineación con el estándar de JavaScript elegido (Airbnb/Google). | Aplicar convenciones específicas de TypeScript, como tipado explícito/inferido, interfaces y minimizar el uso de `any`. |
| **Java** | **[Oracle Code Conventions for the Java TM Programming Language](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html)** o **[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)**. _Se elegirá uno de los dos de forma definitiva._ | Establecer reglas para la estructura del código, comentarios Javadoc, declaraciones, sentencias y formateo. |

---

### Convenciones de Nomenclatura (Naming Conventions)

Se utilizará una convención de nomenclatura **coherente** para cada elemento en el código, basada en las prácticas recomendadas por el estándar de estilo adoptado para cada lenguaje.

| Elemento | Convención (Ejemplo) | Lenguajes Aplicables | Descripción |
| :--- | :--- | :--- | :--- |
| **Variables/Propiedades** | `camelCase` (e.g., `nombreUsuario`, `maxRetries`) | JavaScript, TypeScript, Java | Identificadores que no son constantes. |
| **Constantes** | `SCREAMING_SNAKE_CASE` (e.g., `MAX_SIZE`, `API_KEY`) | JavaScript, TypeScript, Java | Valores inmutables definidos a nivel global o de clase/módulo. |
| **Funciones/Métodos** | `camelCase` (e.g., `calcularTotal`, `guardarDatos`) | JavaScript, TypeScript, Java | Identificadores de funciones y métodos. |
| **Clases/Interfaces** | `PascalCase` (e.g., `UsuarioService`, `AuthInterface`) | TypeScript, Java | Nombres de clases, interfaces, tipos y enums. |
| **Paquetes** | `lowercase` (e.g., `com.empresa.app.utils`) | Java | Nombres de paquetes (totalmente en minúsculas). |
| **Archivos Fuente** | `PascalCase` (e.g., `UserService.ts`, `MainApplication.java`) | TypeScript, Java | Nombres de archivo que contienen una clase o componente principal. |

---

### Herramientas de Automatización del Estilo

Para hacer cumplir estas convenciones y mantener la uniformidad, se utilizarán las siguientes herramientas, que serán integradas en el flujo de desarrollo:

* **CheckStyle**: Considerados para **Java** para el análisis estático y validación del cumplimiento del estándar.

El objetivo es que el **estilo de código sea revisado automáticamente** para que los desarrolladores puedan concentrarse en la lógica del negocio.

### 5.1.4. Software Deployment Configuration.

**Consideraciones Preliminares al Despliegue:**

* **Implementación de Archivos Web:** Se requiere la implementación completa de la página web utilizando archivos HTML, CSS y JS para garantizar su correcta operatividad. Se autoriza el uso de diversos formatos para los archivos de imagen (jpg, png, webp, etc.).
* **Mecanismo de Publicación en Github:** En virtud del servicio Github Pages, todos los archivos necesarios para la funcionalidad de la aplicación se cargarán al repositorio compartido de Github, facilitando la colaboración simultánea entre los miembros del equipo.
* **Protocolo de Pruebas de Funcionamiento:** Tras cada actualización e integración al repositorio, se ejecutarán pruebas internas para asegurar la correcta operación de la página. Asimismo, se someterá la página a pruebas por parte de usuarios externos al grupo de trabajo para obtener una evaluación imparcial.

**Requisitos Mandatorios para el Despliegue:**

* Existencia de un repositorio dentro de la organización de GitHub.
* El repositorio debe poseer visibilidad pública.
* Disposición de los permisos de Github necesarios.
* Disponibilidad del código fuente de la Landing Page.

**Procedimiento de Despliegue de la Landing Page:**

* Carga del código fuente de la Landing Page al repositorio de destino en GitHub.
* Acceso a la interfaz de configuración del repositorio en GitHub.
* Selección de la sección denominada "Pages".
* Una vez completados los pasos precedentes, se iniciará el proceso de construcción, tras el cual la Landing Page deberá estar accesible en breve.

<hr>


## 5.2. Product Implementation & Deployment.
### 5.2.1. Sprint Backlogs

| Sprint #       | Sprint 1 | |                                                            |                                                                                                                   |                     |                   |            |
|----------------|----------|---|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|---------------------|-------------------|------------|
| **User Story** | | **Work-Item/task** |                                                            |                                                                                                                   |                     |                   |            |
| **ID**         | **Title** | **Id** | **Title**                                                  | **Description**                                                                                                   | **Estimation(Hrs)** | **Assigned To**   | **Status** |
| **US-08**      | Ver Información del Startup | T001 | Actualización de startup                                   | Actualizar la información sobre los miembros de la startup pertenecientes al proyecto                             | 1                   | Jefferson Castro  | Done       |
| **US-27**      | Entrar a un dashboard Personalizado | T001 | Mejorar la visualización del dashboard para el propietario | Mejorar el estilo y la estructura funcional del dashboard orientado para el tipo de usuario "Homeowner"           | 1                   | Kenyi Ramirez     | Done       |
|                | | T002 | Mejorar la visualización del dashboard para el proveedor   | Mejorar el estilo y la estructura funcional del dashboard orientado para el tipo de usuario "Provider/Technician" | 2                   | Kenyi Ramirez     | Done       |
| **US-13**      | Registro de cuentas como Dueño de Hogar | T001 | Mejorar la visualización del formulario                        | Actualizar la estructura y estilos del formulario de la sección 'Sign up'                                         | 1                   | Leandro Contreras | Done       |
| **US-17**      | Inicio de sesión de usuarios | T001 | Mejorar la visualización del formulario | Actualizar la estructura y estilos del formulario de la sección 'Sign in'                                         | 1                   | Leandro Contreras | Done       |
| **TS-13**      | Conectar a Base de Datos | T001 | Desplegar el Backend                                       | Actualizar el despliegue de los servicios web (Backend)                                                           | 1                   | Miguel Gomez      | Done       |


| Sprint # | Sprint 2 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User/Technical Story** | | **Work-Item/task** | | | | | |
| **ID** | **Title** | **Id** | **Title** | **Description** | **Estimation(Hrs)** | **Assigned To** | **Status** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **BC Assets (Kenyi)** | | | | | | | |
| **TS-03** | Crear Componente | **T-A-01** | Test Unitario Lógica BC Assets | Implementar tests unitarios (JUnit/Mockito) para las reglas de dominio de Componentes e Inventario. | 4 | Kenyi Ramirez | Done |
| **TS-04** | Actualizar Stock | **T-A-02** | Test Integración/E2E Componentes | Crear escenarios de prueba Karate para verificar endpoints `POST /component` y `PATCH /stock`. | 3 | Kenyi Ramirez | Done |
| **TS-05** | Crear Servicio | **T-A-03** | Test Integración/E2E Servicios | Crear escenarios de prueba Karate para validar la creación de servicios con recetas de componentes. | 3 | Kenyi Ramirez | Done |
| **TS-10** | Stock Automático | **T-A-04** | Test Listener Descuento Stock | Implementar test para el *listener* del evento "Servicio Completado" que descuenta el stock. | 2 | Kenyi Ramirez | Done |
| **BC Service Design (Leandro)** | | | | | | | |
| **TS-06** | Obtener Servicios por Zona | **T-S-01** | Test Unitario Lógica BC Service | Implementar tests unitarios (JUnit/Mockito) para la lógica de búsqueda de servicios por geografía. | 3 | Leandro Contreras | Done |
| **TS-07** | Iniciar Solicitud (Límite) | **T-S-02** | Test Integración Límite de Plan | Crear escenario Karate para validar el límite de solicitudes del Plan Básico (`403 Forbidden`). | 3 | Leandro Contreras | Done |
| **TS-08** | Enviar Solicitud | **T-S-03** | Test Integración/E2E Solicitud | Crear escenarios Karate para el *endpoint* de registro final de una solicitud de servicio. | 4 | Leandro Contreras | Done |
| **BC Profiles (Jefferson)** | | | | | | | |
| **US-23/24** | Gest. Perfil Propietario | **T-P-01** | Test Unitario Lógica BC Profiles | Implementar tests unitarios (JUnit/Mockito) para la lógica de gestión de perfiles de Propietario. | 3 | Jefferson Castro | Done |
| **US-25/26** | Gest. Perfil Técnico | **T-P-02** | Test Integración Perfiles | Crear escenarios Karate para validar la visualización y edición de perfiles de Técnico (`PATCH /profile`). | 4 | Jefferson Castro | Done |
| **BC IAM & Monitoring (Miguel)** | | | | | | | |
| **TS-17/18** | Login/Registro | **T-I-01** | Test Integración Autenticación | Crear escenarios Karate para validar el *endpoint* de Login (JWT) y Registro (roles diferenciados). | 4 | Miguel Gomez | Done |
| **TS-09** | Asignación Automática | **T-I-02** | Test Unitario Lógica Asignación | Implementar tests unitarios para la lógica de asignación automática de técnicos (reglas de stock/prioridad). | 4 | Miguel Gomez | Done |
| **TS-13/Quality** | DB & Static Analysis | **T-I-04** | CheckStyle/SonarQube | Ejecutar el análisis estático** (CheckStyle/SonarQube) para todos los *Bounded Contexts* Java. | 4 | Miguel Gomez | Done |


### 5.2.2. Implemented Landing Page Evidence

Ingresamos a github

<a href="https://ibb.co/C5ZrL2Gh"><img src="https://i.ibb.co/MD4Xd60M/Github1.png" alt="Github1" border="0"></a>

Nos dirijimos a la sección de pages en configuración, configuramos la rama a desplegar y guardamos en save.
Luego de unos minutos de seleccionar "Save", se generará un enlace donde se podrá visualizar el landing page desplegado

<a href="https://ibb.co/8RswyZm"><img src="https://i.ibb.co/Vh9GF4L/github3.png" alt="github3" border="0"></a>

<a href="https://ibb.co/4ZFNj4Yb"><img src="https://i.ibb.co/3yTh0SMx/lp1.png" alt="lp1" border="0"></a>

URL:https://electrolink-diseno-de-experimentos.github.io/Landing-Page/

### 5.2.3. Implemented Frontend-Web Application Evidence

En esta sección, explicamos el despliegue de la aplicación Front-end en firebase

Ulr: https://electrolink-195e0.web.app

Ingresamos al portal de Firebase
<br>

<img src="https://i.ibb.co/tPvdG42H/image.png">
<br>
<br>

Dentro del portal, reutilizamos la aplicación front end previamente desplegada "electrolink-frontend-v2".
<br>

<img src="https://i.ibb.co/xtKnQtdr/image.png">
<br>
<br>

Ahora, desde la consola del IDE, realizamos los siguientes comandos
<br>

<img src="https://i.ibb.co/rfNWtpcp/image.png">
<br>
<br>


Tras haber compilado subido el directorio dist, desplegamos con el siguiente comando y obtendremós el enlace de la aplicación front-end
<br>

<img src="https://i.ibb.co/fdzrZCP6/image.png">
<br>
<br>

Y ya podemos interactuar con nuestro frontend desplegado.

<a href="https://ibb.co/TBSQ6pJ1"><img src="https://i.ibb.co/VWZFRrbx/frontend.png" alt="frontend" border="0"></a>



### 5.2.4. Implemented Native-Mobile Application Evidence

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

Url: https://electrolinkv2.onrender.com/swagger-ui/index.html#

Vista general de Swagger con los grupos Autenticación, Propiedades y Perfiles, cada uno con sus operaciones CRUD protegidas.

#### Deploy de una aplicación en Render
##### 1. Preparar el proyecto en GitHub
1. Asegúrate de tener tu aplicación en un repositorio de **GitHub** (público o privado).
2. Verifica que el proyecto tenga los archivos necesarios:
   - **Dockerfile** (esto debido a que render no acepta java como lenguaje de programación).

##### 2. Crear una cuenta en Render
1. Ve a [https://render.com](https://render.com).
2. Regístrate o inicia sesión (puedes usar tu cuenta de GitHub para mayor comodidad).
3. Autoriza a Render a acceder a tus repositorios de GitHub.

###### 3. Crear un nuevo servicio en Render
1. En el panel de Render, haz clic en **"New +" → "Web Service"**.
[![image.png](https://i.postimg.cc/y8ZSps76/image.png)](https://postimg.cc/hXKjfFJN)
2. Selecciona tu repositorio de GitHub.
[![image.png](https://i.postimg.cc/Xvn7KbJz/image.png)](https://postimg.cc/v4SsMC5r)
3. Configura:
   - **Name**: Nombre de tu aplicación.
   - **Region**: Generalmente elige la más cercana (ej: Oregon).
   - **Branch**: `main` o la rama que quieras desplegar.
   - **Runtime**: Render detecta el lenguaje automáticamente, aunque usaremos Docker debido a la falta de Java (Node, Python, Java, etc.).
   - **Build Command**: El comando para compilar/instalar dependencias. Ejemplos:
     - Node.js: `npm install`
     - Python: `pip install -r requirements.txt`
     - Java (Maven): `./mvnw clean install`
   - **Start Command**: El comando para arrancar tu app.
     - Node.js: `npm start`
     - Python: `gunicorn app:app`
     - Java: `java -jar target/app.jar`

###### 4. Seleccionamos el plan gratuito:
[![image.png](https://i.postimg.cc/Z52XZFkF/image.png)](https://postimg.cc/mP3my9gt)
###### 5. Configurar variables de entorno
1. En Render, abre la sección **"Environment"**.
2. Agrega las variables necesarias (ejemplo: `DATABASE_URL`, `PORT`, `API_KEY`).
3. Si tienes un archivo `.env.example`, úsalo de guía.

##### 6. Deploy automático
1. Render hará el primer build y deploy automáticamente.
2. Si el build es exitoso, Render te dará una **URL pública** con tu app en producción.
3. Cada vez que hagas **push** a la rama configurada, Render redeployará automáticamente tu aplicación.
[![image.png](https://i.postimg.cc/L5W3fD3x/image.png)](https://postimg.cc/fSxdQxFd)

<img  src="https://i.postimg.cc/KzwsXDD0/7c8bebf7-f9bd-4728-a6dc-1c1131947026-1.jpg"/>

Endpoints de Tipos de Componente, Componentes, Roles y Usuarios, listados para gestión y consulta.

<img  src="https://i.postimg.cc/9ffxrnxx/bbde6494-e315-4433-9026-1e3435f0500e-1.jpg"/>

Controladores de Inventario de Técnicos, Servicios, Schedules y Requests, mostrando endpoints CRUD y consultas especializadas.

<img  src="https://i.postimg.cc/HkYzhNCp/d67b08ef-0883-4368-9caa-125775c7863b-1.jpg"/>


### 5.2.6. RESTful API documentation

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **POST** | `/api/v1/catalog/types` | Crear tipo de componente |
| **GET** | `/api/v1/catalog/types` | Obtener todos los tipos de componentes |
| **GET** | `/api/v1/catalog/types/{typeId}` | Obtener tipo de componente por ID |
| **PUT** | `/api/v1/catalog/types/{typeId}` | Actualizar tipo de componente por ID |
| **DELETE** | `/api/v1/catalog/types/{typeId}` | Eliminar tipo de componente por ID |
| **POST** | `/api/v1/catalog/components` | Crear componente |
| **GET** | `/api/v1/catalog/components` | Obtener todos los componentes |
| **PUT** | `/api/v1/catalog/components/{componentId}` | Actualizar componente por ID |
| **DELETE** | `/api/v1/catalog/components/{componentId}` | Eliminar componente por ID |

---

### Technician Inventory

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **POST** | `/api/v1/technicians/{technicianId}/inventory` | Crear inventario de técnico |
| **GET** | `/api/v1/technicians/{technicianId}/inventory` | Obtener inventario de técnico |
| **POST** | `/api/v1/technicians/{technicianId}/inventory/stock-items` | Agregar ítem al stock |
| **PUT** | `/api/v1/technicians/{technicianId}/inventory/{componentId}` | Actualizar componente del inventario |
| **DELETE** | `/api/v1/technicians/{technicianId}/inventory/{componentId}` | Eliminar componente del inventario |

---

### Properties

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/owners/{ownerId}/properties` | Obtener propiedades de un propietario |
| **POST** | `/api/v1/owners/{ownerId}/properties` | Crear propiedad |
| **GET** | `/api/v1/owners/{ownerId}/properties/{propertyId}` | Obtener propiedad por ID |
| **PUT** | `/api/v1/owners/{ownerId}/properties/{propertyId}` | Actualizar propiedad |
| **PUT** | `/api/v1/owners/{ownerId}/properties/{propertyId}/photo` | Actualizar foto |
| **PUT** | `/api/v1/owners/{ownerId}/properties/{propertyId}/address` | Actualizar dirección |
| **DELETE** | `/api/v1/owners/{ownerId}/properties/{propertyId}` | Eliminar propiedad |

---

### Technicians

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/technicians/{technicianId}` | Obtener técnico por ID |
| **POST** | `/api/v1/technicians` | Crear técnico |
| **GET** | `/api/v1/technicians` | Obtener todas las categorías |
| **GET** | `/api/v1/technicians/{technicianId}/works` | Obtener trabajos por técnico |

---

### Works

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/works/{workId}` | Obtener trabajo por ID |
| **POST** | `/api/v1/works` | Crear nuevo trabajo |
| **GET** | `/api/v1/works` | Obtener todos los trabajos |
| **POST** | `/api/v1/works/{workId}/image` | Agregar imagen a un trabajo |

---

### Ratings

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **POST** | `/api/v1/ratings/{id}/rating` | Crear calificación |
| **GET** | `/api/v1/ratings/{id}/rating` | Obtener calificación por ID |
| **GET** | `/api/v1/ratings/technician/{technicianId}/ratings` | Obtener calificaciones por técnico |
| **DELETE** | `/api/v1/ratings/{id}` | Eliminar calificación |
| **PUT** | `/api/v1/ratings/{id}` | Actualizar calificación |
| **GET** | `/api/v1/ratings` | Obtener todas las calificaciones |

---

### Reports

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **POST** | `/api/v1/reports/{id}/report` | Crear reporte |
| **GET** | `/api/v1/reports/{id}` | Obtener reporte por ID |
| **DELETE** | `/api/v1/reports/{id}` | Eliminar reporte |
| **POST** | `/api/v1/reports/{id}/photo` | Agregar foto al reporte |
| **GET** | `/api/v1/reports` | Obtener todos los reportes |

---

### Service Operations

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **POST** | `/api/v1/service-operations` | Crear operación de servicio |
| **GET** | `/api/v1/service-operations` | Obtener todas las operaciones |
| **PUT** | `/api/v1/service-operations/{id}/status` | Actualizar estado de la operación |
| **GET** | `/api/v1/service-operations/{id}/status` | Obtener estado de la operación |
| **GET** | `/api/v1/service-operations/technician/{technicianId}/history` | Obtener historial del técnico |

---

### Requests

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/requests/{requestId}` | Obtener solicitud por ID |
| **PUT** | `/api/v1/requests/{requestId}` | Actualizar una solicitud |
| **DELETE** | `/api/v1/requests/{requestId}` | Eliminar una solicitud |
| **GET** | `/api/v1/requests/client/{clientId}` | Obtener solicitudes por cliente |
| **POST** | `/api/v1/requests` | Crear nueva solicitud |

---

### Schedules

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/schedules/technician/{technicianId}` | Obtener agenda por técnico |
| **POST** | `/api/v1/schedules` | Crear nueva agenda |
| **PUT** | `/api/v1/schedules/{scheduleId}` | Actualizar agenda |
| **DELETE** | `/api/v1/schedules/{scheduleId}` | Eliminar agenda |

---

### Services

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| **GET** | `/api/v1/services/{serviceId}` | Obtener servicio por ID |
| **PUT** | `/api/v1/services/{serviceId}` | Actualizar servicio |
| **DELETE** | `/api/v1/services/{serviceId}` | Eliminar servicio |
| **POST** | `/api/v1/services` | Crear nuevo servicio |

---
Detalle del POST /authentication/sign-up, con ejemplo de JSON de registro y respuesta de usuario creado.

<img  src="https://i.postimg.cc/3w6ZWJ0R/280218fe-28da-435d-89fd-97c9291e768f-1.jpg"/>

Detalle del POST /authentication/sign-in, mostrando el JSON de login y la respuesta con token JWT.

<img  src="https://i.postimg.cc/RhmKn3SM/bc809343-f09e-4a50-bb44-82149c52651f-1.jpg"/>

Detalle del POST /properties para crear una propiedad, con payload de dirección completo y respuesta 201.

<img  src="https://i.postimg.cc/4x0cQ2f2/f39078a9-2159-482b-b12d-f41c80e8ae14-1.jpg"/>

Detalle del POST /components, ilustrando la creación de un componente con su tipo y estado activo.

<img  src="https://i.postimg.cc/SQGzvxQM/d6a73e71-b447-4a97-ab90-529e7c740af7-1.jpg"/>

Detalle del POST /technician-inventories, devolviendo el inventario creado con stocks y umbrales.

<img  src="https://i.postimg.cc/q7nNXkZg/5122357d-b0d4-4693-9a73-48af8880b67d.jpg"/>

Detalle del POST /requests, con estructura completa de solicitud de servicio (factura, fotos, fechas).

<img  src="https://i.postimg.cc/8P0c2F2j/df562760-3766-4933-966f-8805fb761cbd.jpg"/>

Detalle del POST /services, mostrando la creación de un servicio con política, restricciones, etiquetas y componentes asociados.

<img  src="https://i.postimg.cc/QMLtM2xD/335c4d6a-fb9a-45cd-9a47-8997896e5376.jpg"/>


### 5.2.7. Team Collaboration Insights

Durante este Sprint, el equipo ha colaborado en el soporte de la Landing Page, Frontend y Backend. Las actividades fueron gestionadas a través de GitHub, permitiendo una trazabilidad clara de los aportes de cada miembro del equipo. Se realizaron tareas de codificación, revisión, organización del repositorio y mejoras visuales y funcionales del producto. Cada miembro del equipo tuvo participación activa, realizando commits, revisando código, y apoyando en la estructura y documentación del proyecto.

- Insights de Landing Page:

<a href="https://ibb.co/20vmC3mP"><img src="https://i.ibb.co/fVkBydBt/i1.png" alt="i1" border="0"></a>

- Insights de Frontend:
- 
<a href="https://ibb.co/pjFPWtQN"><img src="https://i.ibb.co/VY4NH7xb/i2.png" alt="i2" border="0"></a>

- Insights de Backend:
- 
<a href="https://ibb.co/nN8dCNNy"><img src="https://i.ibb.co/YFTnZFFS/i3.png" alt="i3" border="0"></a>

## 5.3. Video About-the-Product

**Video publicado en Microsoft Stream:**  
[Ver video del producto](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202318323_upc_edu_pe/EaX2Zgimos9BtP8A_A6NVnAB6Q4or5MhvSJrmp8EnSKkEg?e=poBWky&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Video en YouTube (incrustado en el Landing Page):**  
[https://www.youtube.com/watch?v=vajqovVXk3o](https://www.youtube.com/watch?v=vajqovVXk3o)

**Duración del video:** 2 minutos y 35 segundos



# Capítulo VI: Product Verification & Validation

## 6.1 Testing Suites & Validation

La suite de pruebas es el medio o la estructura utilizada para llevar a cabo el proceso de validación. La validación es el objetivo final que determina si la aplicación satisface las necesidades del usuario, y las suites de pruebas son los grupos organizados de casos de prueba que se ejecutan para lograr esa validación. En los siguientes capitulos se mostraran el codigo de las pruebas unitarias.

### 6.1.1 Core Entities Unit Tests

#### Test Unitarios del Bounded Context de Monitoring

En esta imagen se puede visualizar el resultado de éxito de lo 42 unit test implementados para el bounded context de monitoring
[![image.png](https://i.postimg.cc/fTjhTVcL/image.png)](https://postimg.cc/qzRF1MZV)

Aquí se puede ver algunos ejemplos de algunos pruebas unitarias que resaltan sobre otra de este bounded context.

En esta imagen se prueba el servicio de que un service operation que será usado para colocarle un rating tiene que tener el estado COMPLETED, ya que no se puede evaluar un trabajo que no haya finalizado
[![image.png](https://i.postimg.cc/MK41HGzJ/image.png)](https://postimg.cc/xcvXFnk6)

En esta imagen se muestra la prueba unitaria para crear un report de un service operation. La validación de la existencia de este service operation es puesta a prueba para poder generarlo.
[![image.png](https://i.postimg.cc/rs2F3vk3/image.png)](https://postimg.cc/dknYTNDj)

En esta imagen se actualiza el estado de un service operation a COMPLETED, lo que conlleva cambios en otros campos como completedAt para mantener el registro de procesos.
[![image.png](https://i.postimg.cc/rsf3xrQ1/image.png)](https://postimg.cc/bS2mjsXr)

#### Test Unitarios del Bounded Context de Service Design and Planning (SDP)

Se puede apreciar el resultado de éxito de los 32 unit test implementado para el bounded context de service design and planning.

En esta validamos los request command service
<img src = "https://i.postimg.cc/yYSwpv6M/unit1c.png" />

Luego para Schedule Command service
<img src = "https://i.postimg.cc/QCKnPdDV/unit2c.png"/>

Y Finalmente para Service Command service
<img src = "https://i.postimg.cc/rFXkkvH2/unit3c.png"/>

Ahora continuamos con los queryService

Request Query Service:
<img src = "https://i.postimg.cc/y6RMvL8P/unit1q.png"/>

Schedule Query Service:
<img src = "https://i.postimg.cc/DZXMpznc/unit2q.png"/>

Service Query Service:
<img src = "https://i.postimg.cc/9XykGzLb/unit3q.png"/>


#### Test Unitarios del Bounded Context de Assets

Se puede apreciar el resultado de éxito de los unit test implementado para el bounded context de Assets.

ComponentCommandServiceImplTest:
[![image.png](https://i.postimg.cc/DyDvqP3b/image.png)](https://postimg.cc/F7yXvcR9)

ComponentTypeCommandServiceImplTest:
[![image.png](https://i.postimg.cc/mZPCRVjC/image.png)](https://postimg.cc/SjpJf6wx)

TechnicianInventoryCommandServiceImplTest:
[![image.png](https://i.postimg.cc/HxDDx65J/image.png)](https://postimg.cc/JyqdYcpm)

### 6.1.2 Core Integration Tests

#### Tests de integración del Bounded Context de Iam
En este apartado se visualiza el resultado positivo de las pruebas realizadas en karate usando el formato gherkin.
[![image.png](https://i.postimg.cc/Rh95mmD5/image.png)](https://postimg.cc/vgPS7Jy3)

En las siguientes imagenes se visualiza en mayor detalle cada prueba en el reporte que genera karate.

Pruebas de integración para SIGN-UP
[![image.png](https://i.postimg.cc/8P6W9Sgy/image.png)](https://postimg.cc/w797RnvJ)

Pruebas de integración para SIGN-IN
[![image.png](https://i.postimg.cc/SKvCHNR1/image.png)](https://postimg.cc/KKt1Mbnt)

Pruebas de integración para ROLES
[![image.png](https://i.postimg.cc/SK3YDTtj/image.png)](https://postimg.cc/hJ8GGrnq)

Pruebas de integración para USERS
[![image.png](https://i.postimg.cc/HszJfsP3/image.png)](https://postimg.cc/nCscmZxQ)

#### Tests de integración del Bounded Context de Monitoring
En este apartado se visualiza el resultado positivo de las pruebas realizadas en karate usando el formato gherkin.

Aqui se puede ver la prueba de integracion del controller de service operations
[![image.png](https://i.postimg.cc/c4zWKpKq/image.png)](https://postimg.cc/bs1WWFHL)

[![image.png](https://i.postimg.cc/FRTqMS3v/image.png)](https://postimg.cc/62GYRyMb)

Aqui se puede ver la prueba de integración del controller de ratings
[![image.png](https://i.postimg.cc/502KStTy/image.png)](https://postimg.cc/GB6jcbcn)

[![image.png](https://i.postimg.cc/QdZ6nmwK/image.png)](https://postimg.cc/hfMbXLSK)

#### Test de integracion del bounded context de service desing and planning

Comenzamos con los ratings:
<img src = "https://i.postimg.cc/MGkX4jKM/inventory-Runner.png"/>
<img src = "https://i.postimg.cc/CM6hXfmG/karate4.png"/>

Seguimos con los services:
<img src = "https://i.postimg.cc/HxkmPp5W/service-Runner.png"/>
<img src = "https://i.postimg.cc/hGb45y5r/karate1.png"/>

Ahora schedules:
<img src = "https://i.postimg.cc/vBNJq5bq/schedule-Runner.png"/>
<img src = "https://i.postimg.cc/1z5Rbch7/karate2.png"/>

Finalmente con request (clients):
<img src = "https://i.postimg.cc/PrWtxFtT/request-Runner.png"/>
<img src = "https://i.postimg.cc/C1n0VcvX/karate3.png"/>


#### Tests de integración del Bounded Context de Assets
En este apartado se visualiza el resultado positivo de las pruebas realizadas en karate usando el formato gherkin.

En las siguientes imagenes se visualiza en mayor detalle cada prueba en el reporte que genera Karate.

Pruebas de integración para COMPONENTS 
[![image.png](https://i.postimg.cc/K8pQJ48g/image.png)](https://postimg.cc/w1JhBqJ6)

[![image.png](https://i.postimg.cc/SQWh3b9T/image.png)](https://postimg.cc/bdNWSM3k)

Pruebas de integración para TECHNICIAN INVENTORY
[![image.png](https://i.postimg.cc/FsWnnTPQ/image.png)](https://postimg.cc/nCmkXGbd)

[![image.png](https://i.postimg.cc/63pvSfjf/image.png)](https://postimg.cc/GB6tTG14)


### 6.1.3 Core Behavior-Driven Development

A continuación se mostrarán los archivos .feature los cuales usan el formato gherkin.

#### Behavior-Driven Development para Bounded Context de Iam

Aqui se prueban las funcionalidades de Sign-up happy path, sin roles, fallos de username, password y formato.
[![image.png](https://i.postimg.cc/65tcrqv0/image.png)](https://postimg.cc/XX193VxG)

Aqui se prueban las funcionalidades de Sign-in relacionadas a happy path, contraseña incorrecta, usuario inexistente y request incompleto
[![image.png](https://i.postimg.cc/gk2RcZRJ/image.png)](https://postimg.cc/Cd9dmdcT)

Aqui se prueban las funcionalidades de Roles como Validación de token y los fallos de su mal formato
[![image.png](https://i.postimg.cc/zGJJYCRL/image.png)](https://postimg.cc/WhHRMJ8j)

Aqui se prueban las funcionalidades de Users como Get All Users, Get By Id, fallos con el token y no encontrado.
[![image.png](https://i.postimg.cc/gcDSB3m2/image.png)](https://postimg.cc/c6vBvgvp)

#### Behavior-Driven Development para Bounded Context de Monitoring

Aqui se prueban las funcionalidades de Service Operation como el Create, GetById, Update y GetByTechnicianId
[![image.png](https://i.postimg.cc/76bdyVDv/image.png)](https://postimg.cc/hzWpLVfM)

[![image.png](https://i.postimg.cc/QdtpmnJR/image.png)](https://postimg.cc/xcwJT57R)

Aqui se prueban la funcionalidad de Rating como Create.
[![image.png](https://i.postimg.cc/L4x5D4Q6/image.png)](https://postimg.cc/PN8drHkB)

#### Behaivor-Driven Development para Bounded Context Service Design and pLanning

- Peticiones al inventario del técnico:
<img src = "https://i.postimg.cc/T31HSpHM/inventory-feature.png"/>

- Solicitudes que realizan los clientes para contactar a un técnico:
<img src = "https://i.postimg.cc/sfJ6gpkr/client-feature.png"/>

- Crear y/o modificar el horario de atención de un técnico:
<img src = "https://i.postimg.cc/T12cD4zX/schedule-feature.png"/>

- Catálogo de servicios del técnico:
<img src = "https://i.postimg.cc/NF01MrHV/tech-service-feature.png"/>

#### Behaivor-Driven Development para Bounded Context Assets

**Aqui se prueban las funcionalidades de Components como el Create, Update y Delete**:

[![image.png](https://i.postimg.cc/8ctJbJmP/image.png)](https://postimg.cc/D44wvzNt)

[![image.png](https://i.postimg.cc/W4vNhp0r/image.png)](https://postimg.cc/QFfGz34x)


**Aqui se prueban las funcionalidades de Technician Inventory**

- Crear Componente :
  
[![image.png](https://i.postimg.cc/rzXbQsV5/image.png)](https://postimg.cc/5QgntxFt)

[![image.png](https://i.postimg.cc/PJssF2Kw/image.png)](https://postimg.cc/9RpnDP6m)


- Actualizar Stock de componentes:
  
[![image.png](https://i.postimg.cc/ryJQHfh6/image.png)](https://postimg.cc/RqW76L5G)

[![image.png](https://i.postimg.cc/rp1Srp3r/image.png)](https://postimg.cc/R306rvMS)

[![image.png](https://i.postimg.cc/VL00t603/image.png)](https://postimg.cc/Whj4Lsnn)


- Registro de inventario de componente:
  
[![image.png](https://i.postimg.cc/yxcJwpKk/image.png)](https://postimg.cc/7JPYzVfk)

[![image.png](https://i.postimg.cc/RVvVSZQt/image.png)](https://postimg.cc/vDSdXMK8)


### 6.1.4 Core System Tests

En este apartado nos encargamos de realizar algunas pruebas de integración usando Selenium para interactuar con el front y el formato de StepDefinitions usando Gherkin para facilitar la interacción.

##### SignUp

- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/pdZMGxSF/image.png)](https://postimg.cc/SXJPj0kS)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/9FZmP3cG/image.png)](https://postimg.cc/569W1RY0)

- Step Definitions
[![image.png](https://i.postimg.cc/YSVZy93f/image.png)](https://postimg.cc/94dLDcsr)

##### SignIn
- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/6QRftpKL/image.png)](https://postimg.cc/p9WFBxpp)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/XJ4dWKQj/image.png)](https://postimg.cc/CZrzHq3X)

- Step Definitions
[![image.png](https://i.postimg.cc/260bfs1C/image.png)](https://postimg.cc/TLWYVHjs)

##### CreateSchedule
- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/vm3H1WGQ/image.png)](https://postimg.cc/ns9tg9s5)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/dV9TBZJB/image.png)](https://postimg.cc/Yvh929GG)

- Step Definitions
[![image.png](https://i.postimg.cc/dtPkcj1N/image.png)](https://postimg.cc/NLDf1TRR)
[![image.png](https://i.postimg.cc/k54Dvj1r/image.png)](https://postimg.cc/dhbqq9cn)

##### SearchScheduleById
- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/RVgBLvjL/image.png)](https://postimg.cc/SJY3ybQn)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/Hk8h8HH1/image.png)](https://postimg.cc/68w0FkyM)

- Step Definitions
[![image.png](https://i.postimg.cc/WbC9vKZg/image.png)](https://postimg.cc/ykhhhLv8)
[![image.png](https://i.postimg.cc/85p44V8p/image.png)](https://postimg.cc/jW1yqmdm)

##### CreateService
- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/J7BxQxv5/image.png)](https://postimg.cc/jCtyxHsD)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/Nfc6kc19/image.png)](https://postimg.cc/pys5P3cR)

- Step Definitions
[![image.png](https://i.postimg.cc/SK2YpTWW/image.png)](https://postimg.cc/XZWYfg1J)
[![image.png](https://i.postimg.cc/ZKwWvtHF/image.png)](https://postimg.cc/1fNmbdLf)

##### SearchService
- Resultado de la prueba en el Front
[![image.png](https://i.postimg.cc/bvkYTK08/image.png)](https://postimg.cc/B8ZGZ7ww)

- Feature en formato Gherkin con el resultado
[![image.png](https://i.postimg.cc/3JqKHK91/image.png)](https://postimg.cc/D8qVr394)

- Step Definitions
[![image.png](https://i.postimg.cc/FzRQ2qS4/image.png)](https://postimg.cc/cgVj3FT9)

# Capítulo VI: Static Testing & Verification

## 6.2 Static testing & Verification

Esta sección se centra en los métodos de prueba estática y verificación del código, asegurando que el *software* cumpla con los estándares de calidad y seguridad antes de su ejecución. Estos métodos permiten identificar defectos en una fase temprana del ciclo de vida del desarrollo.

### 6.2.1 Static Code Analysis

El análisis estático es una fase obligatoria en nuestra *pipeline* de Integración Continua (CI). Para garantizar el cumplimiento de nuestros estándares, nos apoyamos en herramientas y convenciones específicas.

#### 6.2.1.1 Coding standard & Code conventions

Las normas de codificación y las convenciones son directrices que los desarrolladores deben seguir para garantizar un código legible, mantenible y coherente.

| Lenguaje | Estándar / Convención Adoptada | Herramienta de Aplicación | IDE / Plugins Usados |
| :--- | :--- | :--- | :--- |
| **Java** | **Google Java Style Guide** (Definitivo) | **CheckStyle** (Integrado en el *build*) | **IntelliJ IDEA** (con plugin de CheckStyle), **Visual Studio Code** |

**Principios de Codificación Clave:**

* **Clean Code:** Utilizamos nombres claros y descriptivos (`camelCase` para variables, `PascalCase` para clases, `SCREAMING_SNAKE_CASE` para constantes). Las funciones deben ser cortas y enfocarse en una sola responsabilidad, eliminando código muerto y comentarios superfluos.
* **Domain-Driven Design (DDD) (Backend Java):** Empleamos un **lenguaje ubicuo** que refleja los términos del negocio. La arquitectura se divide en *bounded contexts*, y la lógica del dominio es gestionada por *Servicios de Dominio* y *Repositorios*, promoviendo un diseño organizado.
* **Convenciones en Archivos:** Se sigue el formato `PascalCase` para archivos fuente de clases principales (`UserService.java`) y `lowercase` para paquetes.

---

Para este apartado se evaluará el uso de checkstyle en nuestro proyecto guiados por las convenciones de google_checks.xml
[![image.png](https://i.postimg.cc/gJFHt2xG/image.png)](https://postimg.cc/t1k6Yydc)

##### CheckStyle de Bounded Context Monitoring

En esta imagen se ve que se aplico el comando mvn checkstyle:check para verificar los estilos.
El bounded context de MONITORING y sus errores debería aparecer entre ASSETS y PROFILES, lo que indica que ya no tiene errores sobre sus convenciones.
[![image.png](https://i.postimg.cc/bYKpCXTq/image.png)](https://postimg.cc/XXcRqzmP)

#### ChecStyle de Bounded Context Service Design and Planning
<img src = "https://i.postimg.cc/fyWgzfYv/stylech.png"/>

#### 6.2.1.2 Code Quality & Code Security

Esta es una imagen del code standard de SonarQube para nuestro proyecto.
Representa el estado actual del mismo.
[![image.png](https://i.postimg.cc/0ySKQRkS/image.png)](https://postimg.cc/3kKxSqDr)


### 6.2.2 Reviews

Las revisiones de código son un proceso fundamental para garantizar la calidad del *software* y la conformidad con las normas de codificación establecidas (como la **Google Java Style Guide** y **Airbnb JavaScript Style Guide**). En el proyecto ElectroLink, este proceso se integra directamente con el flujo de trabajo en **GitHub** mediante **Pull Requests (PR)** y se apoya en revisiones tanto manuales como automatizadas.

### Tipos de Revisiones y Herramientas

| Tipo de Revisión | Descripción y Propósito | Herramientas Utilizadas |
| :--- | :--- | :--- |
| **Revisión de Código por Pares (Manual)** | Un desarrollador revisa los cambios de otro a través de un **Pull Request (PR)** en GitHub. Se enfoca en la **claridad, legibilidad y el cumplimiento de las convenciones** de nomenclatura y estructura (`Clean Code`, `DDD`). | **GitHub Pull Requests**, **IntelliJ IDEA** (para inspección local). |
| **Revisión Automatizada** | Se utiliza para escanear el código y garantizar que cumple con los **estándares técnicos de calidad y seguridad**. | **CheckStyle** (para Java), integrados vía **GitHub Actions** en la *pipeline* de CI. |

### Proceso de Revisión (Flujo del Pull Request)

El proceso de revisión está diseñado para ser eficiente y bloquear la integración de código defectuoso o inconsistente:

1.  **Creación del Pull Request (PR):** Los desarrolladores, siguiendo la convención de ramas (`feature/nombre-corto-descriptivo`), crean un PR desde su rama de trabajo hacia la rama objetivo (`release/x.y.z` o `main`).
    * **Mandatorio:** El PR debe incluir una **descripción clara** de la *User Story* o *Work-Item* resuelto y una referencia a las pruebas asociadas (`JUnit`, `Karate`).
2.  **Ejecución de la Pipeline de CI:** Al abrir el PR, **GitHub Actions** se activa automáticamente, ejecutando las fases de *Static Analysis* (**CheckStyle/ESLint**) y la *Test Suite* (`JUnit`, `Karate`).
3.  **Checklist de Revisión:** El revisor designado utiliza un *checklist* mental o físico que cubre aspectos esenciales antes de dar la aprobación manual:
    * Verificación de la lógica de negocio y el impacto del cambio.
    * Comprobación del cumplimiento de las **convenciones de nomenclatura** (ej. `camelCase` en métodos).
    * Validación de la **cobertura de pruebas** unitarias y de integración.
4.  **Comentarios y Feedback:** Los revisores deben proporcionar *feedback* **constructivo y específico** dentro de la interfaz de GitHub. Todo *comment* de bloqueo debe ser resuelto y marcado como tal por el autor antes de la aprobación.
5.  **Aprobación o Rechazo de PR:** El PR debe ser aprobado por **al menos un revisor adicional** antes de que el código pueda fusionarse (*Merge*) a la rama principal (siguiendo el modelo GitFlow adoptado).

### Criterios de Aceptación

Para que un **Pull Request** pueda ser aprobado y fusionado, debe satisfacer los siguientes criterios que garantizan la calidad del código:

* **Calidad de Código y Convenciones:** El código debe superar el análisis estático (**CheckStyle**) y adherirse al 100% de las convenciones de la guía de estilo para el lenguaje correspondiente.
* **Aprobación de la Pipeline de CI:** Todas las etapas de **GitHub Actions** (Análisis Estático, *Build* y *Tests*) deben pasar exitosamente.
* **Cobertura de Pruebas:** Se exige una cobertura de pruebas adecuada (idealmente **superior al 80%**) para asegurar que la nueva funcionalidad esté cubierta y que el cambio no haya roto la funcionalidad existente (*regresión*).

### Frecuencia de Revisiones

Las revisiones de código se realizan de forma **continua e incremental**. El objetivo es mantener el tamaño del PR pequeño, por lo que las revisiones se realizan tan pronto como un desarrollador finaliza su tarea y crea el PR. Esto previene la acumulación de código, facilita la detección temprana de defectos y asegura que el repositorio se mantenga en un **estado de integración constante y de alta calidad**.

---


### 6.3.1. Diseño de Entrevistas.

# Entrevistas por Segmento - Plataforma ElectroLink

## Segmento: Clientes

1. ¿Qué tan fácil te resultó registrarte y entender para qué servía ElectroLink como cliente?
2. ¿Cómo fue tu experiencia al navegar desde el Home hasta encontrar un técnico?
3. Al ver las cards de técnicos, ¿qué información fue clave para tomar una decisión (reseñas, distancia, disponibilidad)?
4. ¿La sección de “Servicios activos” en el dashboard te ayudó a hacer seguimiento de lo que contrataste?
5. ¿Pudiste identificar sin problemas en qué estado estaba tu solicitud o mantenimiento?
6. ¿Sentiste que el diseño de la app era confiable y profesional desde el primer momento?
7. ¿Qué tan útil te pareció el botón “Buscar técnico”? ¿Qué filtro usaste más?
8. ¿La función de geolocalización y mapa te ayudó a elegir al mejor técnico cercano?
9. ¿Te sentiste cómodo contratando a alguien por internet directamente desde la plataforma?
10. ¿Te sirvió el módulo de notificaciones para saber cuándo ocurriría el mantenimiento?
11. ¿Después de recibir el servicio, pudiste calificar al técnico fácilmente?
12. ¿Qué cambiarías en la experiencia visual o funcional para que ElectroLink sea aún más clara o rápida de usar?

---

## Segmento: PYMEs

1. ¿Tu empresa ya tenía una forma de gestionar proveedores eléctricos? ¿Qué cambió con ElectroLink?
2. ¿El dashboard de “Gestión de agenda” te pareció fácil de entender para programar mantenimientos?
3. ¿La opción de ver “Métricas y Rendimiento” fue útil para tomar decisiones de mejora?
4. ¿Consideras valioso poder ver el “Historial de servicios” directamente en la plataforma?
5. ¿ElectroLink te permite tener control sobre los días y horas en que recibes mantenimiento?
6. ¿Qué tan clara te parece la visualización de técnicos preferidos? ¿Los volverías a contratar?
7. ¿La interfaz de búsqueda por tipo de servicio eléctrico y ubicación te pareció ágil?
8. ¿Usaste el sistema de reseñas para elegir a quién contratar? ¿Confiaste en él?
9. ¿Crees que el diseño transmite formalidad y profesionalismo suficiente para una pyme?
10. ¿Qué tan útil sería para ti recibir un reporte automático del mantenimiento realizado?
11. ¿Te sirvió ver alertas de “Notificaciones” como recordatorio de mantenimientos?
12. ¿Qué funcionalidades crees que le hacen falta a ElectroLink para facilitarte la gestión como empresa?

---

## Segmento: Proveedores

1. ¿Fue fácil registrarte como proveedor y configurar tu perfil dentro de ElectroLink?
2. ¿El dashboard de proveedor refleja claramente tu estado (disponible/no disponible, servicios en curso)?
3. ¿Te sentiste representado profesionalmente con el diseño y datos de tu perfil?
4. ¿Qué tan útil te parece tener un módulo específico para gestionar tus servicios activos?
5. ¿La sección de “Inventario y Catálogo” fue fácil de actualizar con tus propios servicios?
6. ¿Consideras útil tener tus “Métricas y Rendimiento” disponibles en tiempo real?
7. ¿Las reseñas de los clientes te han servido para mejorar tu trabajo o conseguir más solicitudes?
8. ¿Qué tan fácil fue para ti agregar un horario a la agenda y gestionar tu disponibilidad?
9. ¿La función de ver tu perfil como los clientes lo ven te parece clara y justa?
10. ¿Pudiste cargar bien tus certificaciones y ver cómo aparecen en la app?
11. ¿Sentiste que la app te dio mayor visibilidad profesional que buscar clientes por tu cuenta?
12. ¿Qué cosas le agregarías al panel de proveedor para sentirte más apoyado como técnico?
---

### 6.3.2. Registro de Entrevistas.
1. Leonardo Prieto<br>

   [image.png](https://postimg.cc/G8vp6Yvf)
    _Entrevista del Frontend Application a Leonardo Prieto_

   Duración: 6:28 min<br>
   Empieza: 00:00

*Resumen de la opinión del entrevistado sobre la aplicación Electrolink*

1. **Comprensión general de la plataforma**:

* Leonardo comprendió rápidamente que **la aplicación conecta clientes con proveedores de servicios eléctricos**, lo cual indica que el objetivo principal está bien comunicado.

2. **Experiencia de usuario (UX)**:

* Destaca que **la interfaz le transmite confianza**, lo cual es clave para cualquier plataforma online. Aunque no profundiza en detalles visuales, su respuesta sugiere que la estructura y navegación iniciales son adecuadas.

3. **Información clave para el usuario**:

* Menciona que **la disponibilidad del técnico** es un factor determinante para tomar decisiones como cliente, lo que sugiere que este dato debería estar muy visible y actualizado en la interfaz.

4. **Funcionalidad destacada**:

* Encuentra **muy útil la opción de búsqueda por localización**, ya que permite identificar técnicos cercanos, algo esencial en servicios presenciales.

5. **Sugerencias de mejora**:

* Sugiere **implementar un sistema de chat en tiempo real** entre técnico y cliente. Esto permitiría una comunicación más fluida, resolver dudas previas al servicio y facilitar la coordinación.
* Propone **añadir imágenes y más información visual** para hacer el apartado visual más atractivo y mejorar el diseño en general.

---

**Análisis general**

Leonardo refleja el perfil de un **usuario potencialmente interesado** en usar la aplicación. Su retroalimentación valida que:

* El **objetivo principal se comunica con claridad**.
* Hay un **mínimo viable funcional** con buen potencial.
* **La confianza en la plataforma es positiva**, aunque aún hay espacio para mejorar la presentación visual.

Además, sus comentarios demuestran que valora:

* La **usabilidad práctica (disponibilidad, localización)**.
* La **comunicación directa (chat)**.
* Una **presentación atractiva (imágenes e información enriquecida)**.

---

2. Piero Tenorio Medina <br>
   [image.png](https://postimg.cc/K4LLy3Z3)
   _Entrevista del Frontend Application a Piero Tenorio_

   Enlace: https://youtu.be/Epc6R8F4hjE <br>
   Duración: 7:53 min<br>
   Empieza: 00:00<br>

*Resumen de la opinión del entrevistado sobre la aplicación Electrolink*

1. **Comprensión general de la plataforma**:

* Piero comprendió rápidamente el proposito de la aplicación, lo cual es el punto deseado..

2. **Experiencia de usuario (UX)**:

* Destaca que la interfaz le transmite confianza, lo cual es clave para cualquier plataforma online. Aunque si reforzaria en lo que la organización visual de algunos elementos.

3. **Información clave para el usuario**:

* Menciona que las secciones para manejar sus componentes electricos son bastante buenas pero considera mejorar la paleta de colores.

4. **Funcionalidad destacada**:

* Encuentra muy útil la sección para agregar componetes a su inventario..

5. **Sugerencias de mejora**:

* Sugiere mejorar la organización visual para poder evitar la fatiga al momento de buscar entre secciones.Asimismo, piensa que es muy importante utilizar mostrar la vista de componentes mediante tablas.

---

**Análisis general**

Leonardo refleja el perfil de un **usuario potencialmente interesado** en usar la aplicación. Su retroalimentación valida que:

* El **objetivo principal se comunica con claridad**.
* Hay un **mínimo viable funcional** con buen potencial.
* **La confianza en la plataforma es positiva**, aunque aún hay espacio para mejorar la presentación visual.

Además, sus comentarios demuestran que valora:

* La **usabilidad práctica (disponibilidad, localización)**.
* La **comunicación directa (chat)**.
* Una **presentación atractiva (imágenes e información enriquecida)**.

---

### 6.3.3. Evaluaciones según heurísticas.

En esta sección, el equipo presenta la evalución en base a las heuristicas de diseño y accesibilidad
<hr>
Evaluación Heurística de ElectroLink

**Carrera:** Ingeniería de Software  
**Curso:** Desarrollo de Aplicaciones Open Source  
**Auditor:** ElectroLink  
**Plataforma evaluada:** ElectroLink – Plataforma Web

---

## Tareas evaluadas

- Comprender el propósito del sitio al ingresar
- Navegar y entender la propuesta de valor tanto para propietarios como para proveedores
- Visualizar e interactuar con el catálogo de servicios
- Acceder a testimonios, valores, misión y visión de la empresa
- Evaluar la visual jerárquica de acciones clave (registrarse, buscar técnicos, mostrar perfil)
- Interacción de proveedores con sus servicios e inventario
- Mostrar el trabajo realizado (visibilidad a clientes)
- Comparar perfiles técnicos y ver reseñas
- Reportar un servicio finalizado (cliente y proveedor)
- Evaluar accesibilidad visual e inclusividad

---

## Tabla resumen de problemas detectados

| #  | Problema detectado                                                                 | Severidad | Heurística/Principio violado                                       |
|----|-------------------------------------------------------------------------------------|-----------|-------------------------------------------------------------------|
| 1  | Falta un botón de regreso rápido al inicio en páginas extensas                     | 2         | Control del usuario                                               |
| 2  | Íconos e imágenes no tienen descripciones accesibles (sin `alt`)                   | 3         | Inclusive Design – Experiencias comparables                      |
| 3  | Jerarquía visual poco clara en botones de acción principal                         | 2         | Visibilidad y jerarquía visual                                    |
| 4  | No hay diferenciación visual clara entre botones de cliente y proveedor            | 2         | Consistencia y estándares                                         |
| 5  | No se explicita claramente el beneficio tangible de publicar un servicio           | 2         | Reconocer en lugar de recordar                                   |
| 6  | En vistas de gestión, no se resalta lo más urgente (como “nuevas solicitudes”)     | 3         | Visibilidad del estado del sistema                               |
| 7  | No hay retroalimentación visual luego de acciones (ej. guardar inventario)         | 3         | Visibilidad del estado del sistema                               |
| 8  | No hay ayudas contextuales (tooltips o descripciones) en íconos de servicios       | 2         | Ayuda y documentación                                             |
| 9  | No se destacan los beneficios diferenciales para PYMEs respecto a clientes comunes | 2         | Reconocer en lugar de recordar / Personalización del contenido    |
| 10 | No se ofrecen opciones de configuración accesibles (contraste, tamaños)            | 3         | Diseño inclusivo                                                  |
| 11 | La opción “Mostrar tu trabajo” no guía claramente cómo se verá al cliente          | 2         | Correspondencia entre sistema y el mundo real                     |
| 12 | El flujo de registro y rol no se valida con confirmación clara al usuario          | 3         | Prevención de errores / Control del usuario                       |

---

## Descripción de problemas clave

### Problema #2: Falta de etiquetas accesibles en íconos e imágenes
**Severidad:** 3  
**Heurística violada:** Inclusive Design  
**Descripción:** Los íconos que representan funcionalidades como “servicio garantizado”, “componentes”, “perfiles”, etc., no tienen `alt` ni descripciones para lectores de pantalla.  
**Recomendación:** Añadir `alt`, `aria-label` o tooltips en cada ícono o imagen decorativa relevante.

---

### Problema #6: No se resalta lo más urgente para el proveedor
**Severidad:** 3  
**Heurística violada:** Visibilidad del estado del sistema  
**Descripción:** En el panel del proveedor, las nuevas solicitudes o acciones pendientes no están resaltadas con prioridad visual.  
**Recomendación:** Usar badges, resaltado en rojo o secciones tipo “acciones recientes”.

---

### Problema #7: No hay retroalimentación visual tras acciones clave
**Severidad:** 3  
**Heurística violada:** Visibilidad del estado del sistema  
**Descripción:** Al guardar componentes, aceptar solicitudes o subir fotos, el usuario no recibe un mensaje inmediato o animación de confirmación.  
**Recomendación:** Mostrar mensajes toast, iconos animados de éxito o loaders donde aplique.


<hr>

<div style="page-break-after: always;"></div>



# Capítulo VII: DevOps Practices

## 7.1. Continuous Integration (CI)

La Integración Continua (CI) es la práctica de fusionar automáticamente los cambios de código en una rama compartida y centralizada de forma regular. Su objetivo es detectar y solucionar errores de integración de manera temprana, manteniendo la calidad y estabilidad del proyecto.

### 7.1.1. Tools and Practices

En nuestro proceso, la CI está impulsada por el desarrollo basado en la metodología **Behavior-Driven Development (BDD)** y **Test-Driven Development (TDD)**, garantizando que el código cumpla con los requisitos del negocio y los estándares técnicos.

| Herramienta | Tipo | Descripción | Propósito en el Proceso |
| :--- | :--- | :--- | :--- |
| **JUnit 5** | Pruebas Unitarias (TDD) | *Framework* estándar de Java para escribir y ejecutar pruebas que validan el comportamiento de pequeñas unidades de código (métodos, clases). | Asegurar la **calidad interna y funcional** de los componentes del *backend* Java (`electrolinkv3`). |
| **Mockito** | Simulaciones (TDD) | Librería de *mocking* que permite crear *mocks* de dependencias externas (bases de datos, servicios, etc.). | Facilitar las pruebas unitarias **aislando la lógica de negocio** para ejecutarlas de forma rápida y confiable. |
| **Karate** | Pruebas de Integración y E2E (BDD) | *Framework* que combina la sintaxis BDD (Gherkin) con pruebas API/Web. Se usa en archivos `.feature` para validar la **integración de *endpoints*** y flujos de negocio. | **Validar el comportamiento del API REST** contra casos de uso definidos en lenguaje Gherkin. |
| **Cucumber / Gherkin** | Metodología BDD | Lenguaje estructurado para describir el comportamiento del *software* en términos de negocio (utilizado a través de Karate). | Garantizar que el desarrollo esté **alineado con las necesidades del negocio** al escribir los escenarios de aceptación. |
| **Visual Studio Code / IntelliJ IDEA** | IDEs principales | Entornos de Desarrollo Integrado que, junto a *plugins* de BDD y Java, facilitan la escritura, depuración y ejecución local de las pruebas. | Aumentar la **productividad del desarrollador** y la ejecución inmediata de pruebas TDD/BDD. |

### 7.1.2. Build & Test Suite Pipeline Components

Nuestra *pipeline* de CI está integrada en **GitHub Actions** y sigue un flujo estricto tras cada *push* a las ramas de desarrollo (`feature/` o `release/`).

| Fase del Pipeline | Descripción | Herramientas Involucradas | Output / Criterio de Éxito |
| :--- | :--- | :--- | :--- |
| **1. Check-out** | Obtiene el código fuente del repositorio (rama `main` o `feature`). | GitHub | Código disponible en el entorno de CI. |
| **2. Static Analysis** | Ejecuta herramientas de análisis estático. | **CheckStyle** (Java)  | **Fallo si** se detectan violaciones graves de estilo o convenciones. |
| **3. Build** | Compila la aplicación *backend* (Java) y genera artefactos. | Maven (`./mvnw clean install`) | **Fallo si** la compilación falla (errores de sintaxis o dependencias). |
| **4. Unit & Integration Tests** | Ejecuta las suites de pruebas. | **JUnit 5** y **Mockito** (Unitarias), **Karate** (Integración/API) | **Fallo si** una prueba unitaria o de integración falla, deteniendo el flujo CI. |
| **5. Containerization** | Construye la imagen de Docker para la aplicación *backend*. | **Docker** | Generación exitosa de la imagen del contenedor, lista para ser desplegada. |

---

## 7.2. Continuous Delivery (CD)

El objetivo de la Entrega Continua (CD) es automatizar la integración y pruebas del código, manteniendo la aplicación lista para un **despliegue manual** a producción en cualquier momento. A diferencia del Despliegue Continuo (Deployment), esta práctica introduce una aprobación final.

### 7.2.1. Tools and Practices

| Herramienta | Tipo | Propósito en Continuous Delivery |
| :--- | :--- | :--- |
| **GitHub Actions** | Automatización CI/CD | Se usa para ejecutar el *pipeline* completo de *build*, *test* y *staging*. Se configura una etapa donde el **despliegue final a producción es manual**. |
| **Render** | Plataforma de Despliegue (Backend) | Se utiliza para el despliegue del *backend* RESTful API (`electrolinkv3.onrender.com`). Garantiza un entorno de producción estable y fácil de gestionar. |
| **Firebase Hosting** | Plataforma de Despliegue (Front-end) | Se utiliza para el despliegue de la aplicación *front-end* (`electrolink-195e0.web.app`). |
| **Docker** | Contenedorización | Asegura la **consistencia del entorno** (Dev, Staging y Producción) para el *backend* Java, facilitando la validación en entornos intermedios. |
| **Trello** | Gestión de Aprobación | Se usa para gestionar el proceso de aprobación. Después de la validación del *pipeline* en *staging*, un Product Owner  debe revisar el build y autorizar manualmente el movimiento del ticket a la columna de Despliegue a Producción. |

**Prácticas Clave:**

* **Feature Branching y Merge Requests:** Los cambios se desarrollan en ramas separadas (`feature/login-ui`) y se integran a una rama estable (`main` o `release`) solo después de pasar todas las pruebas de CI.
* **Pipeline de Validación en Staging:** Tras la CI exitosa, los artefactos se despliegan automáticamente a un entorno de **Staging (Pre-producción)**. Aquí, el equipo puede ejecutar pruebas exploratorias y los interesados pueden validar la funcionalidad, replicando las condiciones de producción (Render, Firebase).
* **Despliegue Semiautomático:** El *pipeline* prepara la aplicación y las imágenes de Docker/artefactos para el despliegue final, pero **no lo ejecuta**. La acción de desplegar a producción se dispara únicamente cuando un desarrollador o administrador **aprueba la *build* validada** en el entorno de *staging*.
* **Aprobación Manual:** Es el punto clave del CD. Antes del despliegue en producción, el *pipeline* requiere una aprobación explícita (a menudo representada por un *Merge Request* a `main` y/o una acción manual en GitHub Actions/Trello) para **reducir el riesgo** de lanzar código no deseado.
* **Rollback Manual:** Aunque la infraestructura de Render y Firebase puede facilitar *rollbacks* rápidos, la decisión y ejecución de un *rollback* en producción son **manuales y controladas** por el equipo, garantizando la supervisión total ante una incidencia.


### 7.2.2 Stages Deployment Pipeline Components

El pipeline de Continuous Delivery en ElectroLink está dividido en etapas claras para garantizar la calidad antes de la aprobación final. Utilizamos Jenkins para la orquestación de la fase de Integración Continua (CI), que es el pilar de este flujo.

**A. Flujo de Integración (CI - Jenkins)**

El proceso inicia tras cada commit con la ejecución del pipeline de CI en Jenkins, garantizando que el código es estable y "desplegable". La imagen muestra la ejecución exitosa de este flujo:

| Etapa del Pipeline (Jenkins) | Objetivo                                                                        |
| :--------------------------- | :------------------------------------------------------------------------------ |
| Checkout SCM                 | Obtener el código actualizado.                                                  |
| Compile Stage                | Construir la aplicación Java/Spring Boot.                                       |
| Testing Stage                | Ejecutar la suite de pruebas (JUnit, Mockito, Karate).                          |
| Package Stage                | Generar el artefacto final (ej. imagen Docker) que será utilizado para el despliegue. |

**B. Componentes de Entrega Continua (Post-CI)**

Una vez que el build es exitoso en Jenkins, el pipeline avanza a las siguientes etapas, orquestadas por GitHub Actions en conjunto con las plataformas de despliegue:

| Componente                         | Descripción                                                                                                                                                                                                                              |
| :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Despliegue a Staging               | Si la CI es exitosa, el backend (Render) y el front-end (Firebase) se despliegan automáticamente al entorno de Staging para la validación de pre-producción.                                                                                 |
| Validación en Staging              | Se realizan pruebas de sistema (System Tests con Selenium) y validaciones manuales/exploratorias para verificar el comportamiento de extremo a extremo, replicando escenarios de producción.                                                  |
| Aprobación Manual de Despliegue    | El pipeline se detiene en este punto. El Product Owner debe revisar los resultados de las pruebas en Staging y dar la aprobación explícita para avanzar a Producción (ej. mediante una gestión en Trello o una acción de aprobación en el sistema de CI/CD). |
| Despliegue Controlado a Producción | Solo tras la aprobación manual, se ejecuta la acción para desplegar la build validada a los entornos de Producción (Render y Firebase).                                                                                                      |



[![image.png](https://i.postimg.cc/2yVsvsFZ/image.png)](https://postimg.cc/tnGvGmcq)

[![image.png](https://i.postimg.cc/C5GQjwnR/image.png)](https://postimg.cc/LgsDSKTS)

### 7.3 Continuous deployment

#### 7.3.1. Tools and Practices.
El Despliegue Continuo (CD) se enfoca en que los cambios aprobados en el código pasen automáticamente desde el desarrollo hasta la producción, garantizando que cada nueva versión sea entregada sin intervención manual, siempre y cuando pase todas las pruebas. En ElectroLink, esta automatización total se reserva para entornos de Desarrollo y Staging.

| Herramienta       | Propósito en el Despliegue Automatizado                                                                                                     |
| :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------ |
| GitHub Actions    | Para automatizar el pipeline de CI/CD. Permite configurar workflows que incluyen la ejecución de pruebas y el despliegue automático a entornos (Development, Staging). |
| Docker            | Para contenerizar la aplicación backend (Spring Boot). Asegura consistencia en los entornos de desarrollo y producción.                       |
| Railway           | Plataforma para la base de datos MySQL. Permite gestionar el despliegue de forma automatizada, con soporte para migraciones y backups.         |
| Render            | Se encarga del despliegue automático del backend en Spring Boot a los entornos intermedios, ofreciendo monitoreo y escalabilidad.              |
| Firebase Hosting  | Para el front-end en Angular, automatiza los despliegues de la aplicación web a entornos intermedios.                                          |

**Prácticas Clave:**

- **Feature Branching:** Utilizamos ramas separadas para el desarrollo. Una vez completadas y probadas, se fusionan a la rama develop o main.

- **Commit-based Deployment:** Cada vez que se realiza un commit en la rama develop (o rama de integración), el pipeline de CI/CD se activa automáticamente para el despliegue a Staging.

- **Rollback Automático:** En caso de detectar fallos post-despliegue en entornos automáticos (como Staging), el pipeline está configurado para realizar un rollback automático, restaurando la versión anterior.

#### 7.3.2. Production Deployment Pipeline Components.

Estos componentes detallan cómo se automatiza el despliegue, incluyendo la Base de Datos, el Backend y el Frontend.

| Componente                         | Flujo de Automatización                                                                                                                                                                                                                              |
| :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Base de Datos (Railway)            | **Gestión de Migraciones Automáticas:** Al modificar entidades, Spring Boot aplica los cambios automáticamente en Railway.<br>**Backup Automático:** Railway crea copias de seguridad antes de aplicar migraciones críticas.                          |
| Backend (Render para Spring Boot)  | **Integración Continua:** Render toma el código de la rama `develop`, lo construye con Maven.<br>**Construcción Docker:** Crea la imagen Docker con todas las dependencias.<br>**Despliegue:** Implementa la nueva versión en el servidor.             |
| Frontend (Firebase para Angular)   | **Compilación:** Firebase CLI construye la aplicación Angular en modo producción.<br>**Pruebas Automatizadas:** Ejecuta pruebas unitarias y E2E.<br>**Despliegue:** Si las pruebas pasan, Firebase implementa automáticamente la nueva versión. |


### 7.4. Continuous Monitoring

#### 7.4.1. Tools and Practices.

## **Tools and Practices**

| Herramienta | Tipo | Propósito en Continuous Delivery |
| :--- | :--- | :--- |
| **Google Analytics** | Herramienta de Análisis Web | Se usa para **ver cómo los usuarios usan la aplicación** después de cada despliegue. Muestra qué páginas visitan, cuánto tiempo permanecen y qué botones clickean. |
| **Event Tracking** | Monitoreo de Acciones | Se configuran **eventos simples** para saber si las nuevas funciones se usan correctamente (ejemplo: "usuario_completo_formulario", "boton_descarga_presionado"). |
| **Dashboard de Métricas** | Panel de Control | Proporciona **reportes fáciles de entender** sobre el uso de la aplicación, ayudando al equipo a ver si los cambios recientes funcionan bien. |

**Prácticas Clave:**

* **Verificación Después del Despliegue:** Después de lanzar nuevos cambios a producción, **revisamos Google Analytics por 1-2 días** para confirmar que los usuarios están usando las nuevas funciones correctamente.

* **Datos para Decisiones:** Si vemos que **los usuarios no usan una función nueva**, podemos decidir mejorarla o explicarla mejor en la siguiente versión.

* **Detección Temprana de Problemas:** Si las **métricas bajan mucho** después de un despliegue, es una señal para investigar si hay errores que no detectamos en pruebas.

* **Validación con Datos Reales:** Usamos la **información real de usuarios** (no solo nuestras suposiciones) para decidir qué mejorar en la aplicación.

* **Monitoreo Continuo:** Revisamos los **reportes semanales** de Google Analytics para entender cómo evoluciona el uso de la aplicación con el tiempo.

#### 7.4.2. Monitoring Pipeline Components

Este es el script que se pondra en el header del proyecto
[![image.png](https://i.postimg.cc/Y2ZTQdXd/image.png)](https://postimg.cc/mh3dsyW9)

Se coloca el script dentro del header
[![image.png](https://i.postimg.cc/Dy1pLn44/image.png)](https://postimg.cc/7fYNyvVq)

Aqui se puede ver los resultados de los analisis de usuarios
[![image.png](https://i.postimg.cc/R05Y2q5m/image.png)](https://postimg.cc/hXsMdDtZ)

#### 7.4.3. Alerting Pipeline Components

El componente de alertas es crucial para la detección y respuesta rápida ante problemas de rendimiento o disponibilidad.

- **Prometheus con Alertmanager:** Prometheus recopila métricas y define umbrales (ej. uso de CPU, latencia). Cuando los límites se exceden, genera alertas que son enviadas a Alertmanager para su gestión y distribución. Alertmanager enruta las notificaciones a distintos canales (Slack, Correo) según la gravedad.

- **Grafana:** Se utiliza para la visualización avanzada de métricas y la configuración de alertas visuales en paneles personalizados. Proporciona una interfaz intuitiva para monitorear y recibir alertas de rendimiento en tiempo real.

#### 7.4.4. Notification Pipeline Components.

El pipeline de notificaciones es esencial para comunicar de forma automática los resultados de las pruebas y el estado del pipeline.

- **Jenkins/GitHub Actions:** Permiten configurar notificaciones detalladas sobre el progreso y los resultados de cada fase del pipeline de pruebas.

- **Alertas en Tiempo Real:** Las notificaciones se configuran para enviarse automáticamente al finalizar cada build o etapa del pipeline, informando sobre el éxito o fallo de las pruebas, facilitando una respuesta inmediata a cualquier incidente.


## 8.1. Experiment Planning

En esta sección, se planifica el enfoque experimental para validar las hipótesis y supuestos clave del proyecto ElectroLink. El objetivo es movernos de las suposiciones a los hechos probados mediante la experimentación.

### 8.1.1. As-Is Summary

El estado actual (As-Is) del dominio de servicios eléctricos en el segmento objetivo presenta una fricción significativa y desconfianza entre los dos actores principales:

-  1. Clientes (Propietarios y PYMES): (Representados por Olivia Pérez y Eduardo Gonzales). Tienen una necesidad crítica de servicios eléctricos, pero su problema central es la dificultad para encontrar proveedores confiables y certificados. Actualmente, recurren a métodos informales (recomendaciones, redes sociales), lo que les genera un alto nivel de ansiedad, incertidumbre y riesgo, resultando a menudo en trabajos de mala calidad o inseguros.

- 2. Proveedores (Técnicos Certificados): (Representado por Alejandro López). Luchan por encontrar un flujo constante de clientes y compiten en desventaja contra un gran mercado informal que ofrece precios más bajos sin garantías. Carecen de herramientas digitales para gestionar sus servicios, construir una reputación verificable y demostrar su certificación de manera efectiva.

La situación actual es un ciclo de desconfianza: los clientes no confían en los técnicos que encuentran, y los técnicos certificados no pueden diferenciarse digitalmente de los informales.

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

Basado en el Lean UX Process (Capítulo 1.2.2) y el As-Is Scenario (Capítulo 2.3.5) definiremos el material en bruto para la experimentación:

**1. Assumptions (Suposiciones Clave):**

 - Suposición de Valor (Cliente): Creemos que los clientes (propietarios y PYMES) valoran más la garantía de un técnico certificado y la seguridad del servicio que un precio bajo.

 - Suposición de Valor (Proveedor): Creemos que los técnicos certificados pagarán una suscripción mensual si les proporcionamos un flujo constante de clientes calificados y herramientas de gestión.

 - Suposición de Adquisición: Creemos que podemos adquirir la mayoría de los clientes a través de estrategias de marketing digital (p.ej., redes sociales, publicidad segmentada).

 - Suposición de Confianza: Creemos que un sistema de reseñas y calificaciones (Hypothesis #1) es fundamental para construir la confianza que los clientes necesitan para contratar.

**2. Knowledge Gaps (Brechas de Conocimiento):**

 - No sabemos el monto exacto (precio) que los técnicos están dispuestos a pagar por la suscripción mensual.

 - No sabemos cuál es el canal de marketing digital más efectivo (Facebook, Google Ads, etc.) y con el menor costo de adquisición (CAC) para captar propietarios de viviendas.

 - No sabemos qué características específicas del perfil de un técnico (además de la certificación) son las que más generan confianza en un cliente al momento de decidir (¿fotos de trabajos, años de experiencia, reseñas?).

 - No sabemos si los propietarios del Plan Básico (gratuito) verán suficiente valor en el "servicio prioritario" (US-57) como para pagar por un Plan Premium.

 - No sabemos si los técnicos (como Alejandro) realmente adoptarán las herramientas de gestión (agenda, inventario) o si preferirán seguir usando sus métodos manuales (WhatsApp, cuaderno).

**3. Ideas:**

 - Implementar un riguroso proceso de validación de certificaciones para todos los técnicos que se registren.

 - Crear un sistema de reseñas y calificaciones de 5 estrellas visible en el perfil público del técnico.

 - Desarrollar un módulo de gestión de agenda e inventario (US-37, US-48) como valor agregado para los técnicos.

 - Ofrecer un modelo "Freemium" para los propietarios (Plan Básico y Premium) para fomentar la adopción.

**4. Claims (Declaraciones):**

 - Nuestra plataforma reducirá los riesgos eléctricos en hogares y PYMES al formalizar la contratación de servicios.

 - ElectroLink romperá el ciclo de informalidad en el sector (Problem Statement #2).

 - El modelo de negocio basado en suscripción para proveedores es   viable y escalable.

### 8.1.3. Experiment Ready-Questions

Transformamos las suposiciones y brechas de conocimiento en preguntas específicas que podemos responder mediante experimentos.

 - **Q1[Viabilidad/Proveedor]:** ¿Pagarán los técnicos certificados una suscripción mensual (p.ej., S/ 50) por acceder a clientes calificados y herramientas de gestión?

 - **Q2[Viabilidad/Cliente]:** ¿Contratarán los propietarios de viviendas un servicio eléctrico a través de la plataforma, basando su confianza en los perfiles verificados y las reseñas?

 - **Q3[Valor/Retención Proveedor]:** ¿Usarán los técnicos activamente las herramientas de agenda e inventario de la plataforma para gestionar sus servicios?

 - **Q4[Adquisición/Cliente]:** ¿Cuál canal de marketing digital (Facebook Ads vs. Google Ads) genera registros de propietarios (leads) al menor costo?

 - **Q5[Crecimiento/Cliente]:** ¿Cuántos propietarios del Plan Básico (con un límite de 2 solicitudes) estarán dispuestos a pagar por el Plan Premium para obtener "servicio prioritario"?

### 8.1.4. Question Backlog

Priorizamos las preguntas anteriores para enfocar nuestros primeros esfuerzos en validar lo más riesgoso e importante para el modelo de negocio.

| Prioridad | ID | Pregunta(Experiment-Ready Question) |
| --------- | -- | ----------------------------------- |
| **Alta** | *Q2* | ¿Contratarán los propietarios de viviendas un servicio eléctrico a través de la plataforma, basando su confianza en los perfiles verificados y las reseñas? |
| **Alta** | *Q1* | ¿Pagarán los técnicos certificados una suscripción mensual (p.ej., S/ 50) por acceder a clientes calificados y herramientas de gestión? | 
| **Media** | *Q3* | ¿Usarán los técnicos activamente las herramientas de agenda e inventario de la plataforma para gestionar sus servicios? |
| **Media** | *Q4* | ¿Cuál canal de marketing digital (Facebook Ads vs. Google Ads) genera registros de propietarios (leads) al menor costo? |
| **Baja** | *Q5* | ¿Cuántos propietarios del Plan Básico (con un límite de 2 solicitudes) estarán dispuestos a pagar por el Plan Premium para obtener "servicio prioritario"? |

### 8.1.5. Experiment Cards

Basados en las preguntas de mayor prioridad (Q2 y Q1), diseñamos los siguientes experimentos:

| Elemento | Experiment Card #1: Validación de Confianza del Cliente | 
| -------- | ---------------------------------------------- |
| **Hypothesis** | *(Basandonos en Q2)* |
| **Experiment** | Creemos que los propietarios de viviendas (como Olivia) contratarán un servicio a través de ElectroLink.<br><br>Porque su mayor frustración actual es la desconfianza y ansiedad que les genera el mercado informal, y nuestra plataforma soluciona eso mostrando perfiles verificados y reseñas reales.<br><br>Para verificar esto, realizaremos una prueba de usabilidad con un prototipo de alta fidelidad (Mockups) del flujo de contratación (US-40 a US-44).<br><br>Presentaremos a 10 usuarios (del segmento "propietarios de hogar") dos perfiles de técnicos (uno verificado y con reseñas; otro nuevo sin reseñas) y les pediremos que "contraten a alguien para una revisión eléctrica". |
| **Metrics** | Mediremos el porcentaje de usuarios que completan el flujo de contratación y el porcentaje que elige al técnico verificado. También registraremos su nivel de confianza reportado (escala 1-5) después de la tarea. |
| **Success Criteria** | Sabremos que estamos en lo correcto si al menos 8 de 10 (80%) usuarios eligen al técnico verificado y reportan un nivel de confianza de 4 o 5 en el proceso. | 

| Elemento | Experiment Card #2: Validación del Modelo de Negocio (Suscripción Proveedor) |
| -------- | ---------------------------------------------- |
| **Hypothesis** | *(Basandonos en Q1)* |
| **Experiment** | Creemos que los técnicos certificados (como Alejandro) pagarán una suscripción mensual.<br><br>Porque la plataforma les garantiza acceso a clientes recurrentes y herramientas de gestión (agenda, inventario), solucionando su problema de inconsistencia de trabajo y falta de digitalización.<br><br>Para verificar esto, realizaremos entrevistas de validación de concepto y precio con 15 técnicos certificados que actualmente trabajen de forma independiente.<br><br>Les mostraremos el prototipo de la plataforma (perfil de cliente, herramientas de gestión) y les presentaremos 3 niveles de precio tentativos (Ej: S/ 25, S/ 50, S/ 100 al mes) después de un mes de prueba gratis. |
| **Metrics** | Mediremos el porcentaje de técnicos que expresen una "alta intención de pago" (verbalmente) por el plan de S/ 50. |
| **Success Criteria** | Sabremos que estamos en lo correcto si al menos 60% (9 de 15) de los técnicos indican que "muy probablemente" o "definitivamente" pagarían la suscripción de S/ 50 tras ver el valor ofrecido. | 


<hr>

### 8.2. Experiment Design

En esta fase se detalla el diseño técnico de los experimentos identificados a partir del Experiment-Ready Questions de la sección anterior. El objetivo es construir un marco metodológico sólido que permita validar o refutar las hipótesis críticas del negocio con significancia estadística.

#### 8.2.1. Hypotheses

A partir de nuestras Asunciones Lean UX (Capítulo 1), hemos refinado las hipótesis de negocio para convertirlas en hipótesis de experimento medibles.

*   **Hipótesis 1 (Adopción del Cliente - Confianza):**
    
    *   **Creemos que** al implementar un sistema de insignias de "Técnico Verificado" (basado en la validación de certificaciones) y mostrar las reseñas de forma prominente en el perfil del proveedor...
        
    *   **Resultará en** un incremento en la confianza percibida por los propietarios (Persona: Olivia Pérez), lo que aumentará la tasa de solicitudes de servicio.
        
    *   **Sabremos que esto es cierto si** la Variante B (con insignias y reseñas destacadas) logra una tasa de conversión de "visita a perfil" a "solicitud de servicio" al menos un 25% mayor que la Variante A (perfil estándar), en un período de 14 días.
        
*   **Hipótesis 2 (Retención del Proveedor - Valor Percibido):**
    
    *   **Creemos que** al proporcionar a los técnicos (Persona: Alejandro López) un dashboard con "Métricas de Oportunidad" (que muestre solicitudes perdidas en su zona y su tasa de aceptación)...
        
    *   **Resultará en** una mayor percepción del valor de la suscripción paga de la plataforma.
        
    *   **Sabremos que esto es cierto si** los técnicos expuestos al nuevo dashboard (Variante B) tienen una tasa de abandono (churn) un 20% menor que el grupo de control (Variante A) después de 30 días de uso.  

| Hipótesis | Pregunta | Belief (Creencia) | Hypothesis (H1) | Null Hypothesis (H0) |
| --- | --- | --- | --- | --- |
| H1 (Adopción Cliente - Confianza) | Q2 | La implementación de insignias de "Técnico Verificado" y reseñas destacadas aumentará la confianza de los propietarios. | La Tasa de Conversión a solicitud de servicio aumentará al menos un 25% con insignias y reseñas destacadas. | La implementación de insignias y reseñas destacadas no aumentará la Tasa de Conversión a solicitud de servicio en un 25% (o más). |
| H2 (Retención Proveedor - Valor Percibido) | Q3 | Proporcionar un dashboard con "Métricas de Oportunidad" incrementará la percepción del valor de la suscripción. | Los técnicos expuestos al nuevo dashboard tendrán una tasa de abandono (churn) un 20% menor después de 30 días de uso. | El nuevo dashboard de Métricas de Oportunidad no reducirá la tasa de abandono (churn) en un 20% (o más). |

#### 8.2.2. Domain Business Metrics

Estas son las métricas de alto nivel (OKRs) que el negocio (ElectroLink) utiliza para medir el éxito general, y que nuestros experimentos buscan impactar.

*   **Tasa de Conversión de Clientes (CCR):** (Número de servicios contratados / Número de visitantes únicos) %.

*   **Tasa de Abandono de Proveedores (Provider Churn Rate):** (% de proveedores que cancelan su suscripción paga por mes).

*   **Tasa de Adopción de Funcionalidades (Feature Adoption Rate - FAR):** (% de usuarios activos que utilizan una nueva funcionalidad clave al menos una vez por semana).

*   **Puntuación Neta del Promotor (NPS):** Medida de la lealtad y satisfacción del cliente (tanto propietarios como técnicos).


#### 8.2.3. Measures

Estas son las métricas de datos crudos (cuantitativas y cualitativas) que recopilaremos directamente durante el experimento para evaluar las hipótesis.

*   **Para Hipótesis 1 (Confianza):**

  *   Clics en el botón "Solicitar Servicio" (por variante).

  *   Número de impresiones (vistas) del perfil del técnico.

  *   Tasa de rebote en la página del perfil.

  *   _Cualitativo:_ Respuestas a encuestas de salida ("¿Qué tan confiable le pareció este perfil?").

*   **Para Hipótesis 2 (Retención):**

  *   Número de clics en la pestaña "Dashboard de Métricas".

  *   Tiempo promedio de sesión dentro del dashboard de métricas.

  *   Clics en el botón "Cancelar Suscripción".

  *   Número de servicios aceptados por el técnico (post-visualización del dashboard).


| Question | Measure |
| --- | --- |
| Q2: ¿Contratarán los propietarios basando su confianza en perfiles verificados y reseñas? | Cuantitativo: Clics en el botón "Solicitar Servicio" por variante. Tasa de Conversión (Visita a Perfil → Solicitud). Tasa de rebote en la página del perfil. Cualitativo: Respuestas a encuestas de salida ("¿Qué tan confiable le pareció este perfil?"). |
| Q3: ¿Usarán los técnicos activamente las herramientas de agenda e inventario? | Cuantitativo: Clics en la pestaña "Dashboard de Métricas". Tiempo promedio de sesión dentro del dashboard. Clics en el botón "Cancelar Suscripción" (medición de churn). |

#### 8.2.4. Conditions

Definimos las condiciones del experimento (grupos de control y variantes) para aislar el impacto de los cambios introducidos.

| Experimento | Condición Experimental (Variante B) | Condición de Control (Grupo A) |
| --- | --- | --- |
| Experimento 1 (Confianza del Cliente - H1) | 50% de propietarios ven el diseño To-Be: Insignia "Verificado por ElectroLink" prominente y reseñas ubicadas directamente debajo de la información de contacto. | 50% de propietarios ven el diseño As-Is: Perfil estándar, con reseñas al final de la página y sin insignias. |
| Experimento 2 (Retención Proveedor - H2) | 50% de técnicos ven el dashboard To-Be: Incluye un nuevo widget de "Métricas de Oportunidad" (solicitudes perdidas en su zona) en la parte superior. | 50% de técnicos ven el dashboard As-Is: Solo muestra lista de servicios pendientes y agenda, sin el nuevo widget de Métricas de Oportunidad. |


#### 8.2.5. Scale Calculations and Decisions

Para asegurar la validez estadística, calculamos el tamaño de muestra necesario.

*   **Decisión de Nivel de Confianza:** 95% (p-value < 0.05).

*   **Decisión de Poder Estadístico:** 80%.

*   **Efecto Mínimo Detectable (MDE):**

  *   Para H1: Buscamos detectar un _lift_ (mejora) relativo del 20% sobre nuestra tasa de conversión base actual del 5%.

  *   Para H2: Buscamos detectar una reducción relativa del 15% en el _churn_ base del 10%.

*   **Cálculo de Muestra (H1):** Se requiere un mínimo de 4,500 visitantes únicos por variante (Total: 9,000).

*   **Cálculo de Muestra (H2):** Se requiere un mínimo de 1,200 técnicos por variante (Total: 2,400).

*   **Duración:** Los experimentos se ejecutarán durante 21 días para capturar el comportamiento de tres ciclos semanales completos y alcanzar el tamaño de muestra requerido.


| Factor | Valor de Decisión | Justificación y Nivel |
| --- | --- | --- |
| Nivel de Confianza (1−α) | 95% | Ideal. Estándar de la industria para asegurar la fiabilidad de los resultados. |
| Poder Estadístico (1−β) | 80% | Aceptable/Ideal. Mínimo requerido para reducir la posibilidad de un Falso Negativo. |
| Efecto Mínimo Detectable (MDE) | H1: Lift relativo del 20% en CCR. H2: Reducción relativa del 15% en Churn. | Ideal. Define el cambio mínimo que se considera valioso para el negocio. |
| Tamaño Muestral Calculado | H1: 9,000 visitantes únicos totales. H2: 2,400 técnicos totales. | Ideal. Muestra calculada para validar el MDE con 95% de confianza. |
| Duración | 21 días | Ideal. Periodo suficiente para alcanzar el tamaño de muestra y cubrir ciclos de comportamiento. |


#### 8.2.6. Methods Selection

| Herramienta | Precio | Capacidad de Análisis | Ventajas | Documentación | Sencillez |
| --- | --- | --- | --- | --- | --- |
| Google Analytics | Plan gratuito/Créditos gratis | Análisis cuantitativo completo y exhaustivo del tráfico y comportamiento del usuario. | Excelente para reportes. Gran capacidad de integración. Medición post-experimento. | Extensa | Aprendizaje sencillo para funciones básicas, complejidad media para análisis avanzados. |
| Optimizely | Basado en suscripción (Plan Starter gratuito) | Plataforma líder para Test A/B, Multivariante y Feature Flagging (Gestión de liberaciones de funcionalidad). | Ideal para la ejecución de experimentos y garantizar la validez estadística. Analítica de impacto directa. | Extensa y técnica | Requiere configuración técnica inicial, pero la interfaz de diseño de experimentos es intuitiva. |
| Qualtrics | Plan gratuito básico (Suscripción Enterprise) | Recolección de datos cualitativos/cuantitativos mediante encuestas avanzadas, formularios y análisis de feedback. | Herramienta de nivel empresarial para mediciones de NPS, satisfacción (CSAT) y recolección de feedback específico post-experimento. | Muy Extensa y académica | Interfaz intuitiva para encuestas, requiere curva de aprendizaje para análisis estadístico avanzado. |
| Hotjar | Plan gratuito con limitaciones | Análisis cualitativo (mapas de calor, grabaciones de sesión, encuestas de feedback visual). | Permite entender el "porqué" detrás del comportamiento del usuario de forma visual, fundamental para la H1 (Confianza). | Buena | Interfaz muy intuitiva y fácil de configurar. |

Tras evaluar cada una de las opciones, elegimos Google Analytics, considerando todas las funcionalidades y la documentación que ofrece. Esto se debe a que esta herramienta tiene un plan gratuito que nos permite obtener datos estadísticos relevantes y sencillos. Además, al ser una herramienta muy usada, hay mucha información disponible sobre su uso e integración en forma de guías, tutoriales y videos.

#### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection

El objetivo analítico es determinar si las variantes (B) producen un resultado estadísticamente superior al control (A), utilizando los KPIs definidos.

| Hipótesis | Objetivo Analítico | KPI Primario (Métrica de Éxito) | Métricas Secundarias (Guardrails) |
| :--- | :--- | :--- | :--- |
| **H1: Perfil Verificado** | Determinar si la confianza visual (insignia) impacta la decisión de contratación. | Tasa de Conversión (Solicitudes / Vistas de Perfil) | Tasa de rebote en perfil, Tiempo en página. |
| **H2: Dashboard Técnico** | Determinar si la provisión de datos de mercado (métricas) reduce el abandono. | Tasa de Abandono (Churn Rate) | Tasa de Adopción de la Funcionalidad (FAR), Tasa de aceptación de servicios. |

#### 8.2.8. Web and Mobile Tracking Plan

Para ElectroLink, el objetivo es monitorear la plataforma web y móvil para validar si los cambios introducidos en los perfiles (H1) y el dashboard de técnicos (H2) generan la confianza y el valor percibido necesarios para sostener el modelo de negocio.

Estableceremos un plan de seguimiento exhaustivo basado en el A/B Testing para evaluar el impacto causal de las mejoras implementadas.

**1. Implementación Inicial**
Durante esta fase, nos enfocaremos en el lanzamiento de los diseños Experimentales y la recolección de datos segmentados para establecer la causalidad de los resultados frente a la Línea Base (Control).
- **Asignación del Grupo:** Todos los eventos críticos incluirán una propiedad que identifica si el usuario está en el grupo Control o Experimental para garantizar que los resultados de cada usuario sean analizados dentro de su grupo asignado.
- **Métricas de Confianza (H1):** Se capturarán los clics en "Solicitar Servicio" (service_request_initiated) y las vistas de perfil (profile_view) para medir la Tasa de Conversión (CCR).
- **Métricas de Valor/Retención (H2):** Se registrarán los clics en el botón "Cancelar Suscripción" (subscription_cancellation_attempt) y la interacción con el nuevo widget (metrics_widget_interaction) para medir el Churn y la adopción.
- **Feedback de Usuarios:** Se implementarán encuestas (ej., Qualtrics o Hotjar) post-interacción para obtener datos cualitativos sobre la confianza percibida tras ver el perfil verificado (H1).

**2. Seguimiento Continuo**
Después de la fase inicial de validación (21 días), se establecerá un proceso continuo de seguimiento para evaluar el rendimiento a largo plazo.
- **Métricas en Tiempo Real:** Se implementarán herramientas de análisis web y móvil (ej., Google Analytics) para monitorear el comportamiento de los usuarios en tiempo real.
- **Segmentación de Usuarios:** Los datos se segmentarán por tipo de usuario (Propietarios, Técnicos, Rol de Suscripción) para entender mejor cómo cada grupo interactúa con las funcionalidades clave.
- **Tasa de Retención a Largo Plazo:** Se medirá la Tasa de Abandono de Proveedores (Provider Churn Rate) a lo largo del tiempo para evaluar la efectividad del nuevo dashboard (H2) en mantener a los técnicos comprometidos con la plataforma.

Este enfoque asegurará que ElectroLink tome decisiones informadas y validadas por datos, centrándose en la viabilidad económica del proyecto.


### 8.3. Experimentation

Esta sección traduce el diseño del experimento en los artefactos de desarrollo (Historias de Usuario y Backlog) necesarios para construir, ejecutar y medir las variantes del experimento.

#### 8.3.1. To-Be User Stories

Estas historias de usuario describen las funcionalidades específicas requeridas para implementar las **Variantes B** de nuestros experimentos.

*   **ID: EXP-US-001 (Relacionada a H1)**
    
    *   **Como** propietaria (Olivia),
        
    *   **Quiero** ver una insignia visual de "Técnico Verificado" y las reseñas más útiles en la parte superior del perfil de un técnico,
        
    *   **Para** poder evaluar su confiabilidad rápidamente y tomar una decisión de contratación más segura.
        
    *   **Criterios de Aceptación:**
        
        *   Dado que un usuario pertenece a la "Variante B" del experimento H1.
            
        *   Cuando carga un perfil de técnico que ha completado la validación de documentos.
            
        *   Entonces el sistema debe mostrar la insignia "Verificado por ElectroLink" junto al nombre.
            
        *   Y el componente de "Reseñas Destacadas" debe aparecer sobre la sección "Servicios Ofrecidos".
            
*   **ID: EXP-US-002 (Relacionada a H2)**
    
    *   **Como** técnico (Alejandro),
        
    *   **Quiero** ver un widget en mi dashboard que resuma las "Oportunidades Perdidas" (solicitudes en mi zona que no acepté o que fueron tomadas por otros),
        
    *   **Para** entender mejor la demanda real y ajustar mi disponibilidad o mi tasa de aceptación de servicios.
        
    *   **Criterios de Aceptación:**
        
        *   Dado que un técnico pertenece a la "Variante B" del experimento H2.
            
        *   Cuando carga su dashboard principal.
            
        *   Entonces el sistema debe mostrar el widget "Métricas de Oportunidad".
            
        *   El widget debe mostrar (como mínimo): "Solicitudes en tu zona (últ. 7 días)" y "Tasa de Aceptación".


| ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Experimento) |
| :--- | :--- | :--- | :--- | :--- |
| **EXP-US-001** | Perfil con Insignia Verificada y Reseñas Destacadas | Como propietaria (Olivia), quiero ver una insignia visual de "Técnico Verificado" y las reseñas más útiles en la parte superior del perfil de un técnico, para poder evaluar su confiabilidad rápidamente y tomar una decisión de contratación más segura. | **Escenario 1: Visualización de la Insignia**<br>• Given el propietario pertenece al grupo Experimental de H1.<br>• When carga un perfil de técnico con certificación validada.<br>• Then el sistema debe mostrar la insignia "Verificado por ElectroLink" de forma prominente junto al nombre del técnico.<br><br>**Escenario 2: Priorización de Reseñas**<br>• Given el propietario está en el grupo Experimental.<br>• When la página del perfil se carga.<br>• Then el componente de "Reseñas Destacadas" debe ser el segundo elemento visible en el viewport (sobre la sección "Servicios Ofrecidos"). | H1 (Confianza del Cliente) |
| **EXP-US-002** | Widget de Métricas de Oportunidad para Técnicos | Como técnico (Alejandro), quiero ver un widget en mi dashboard que resuma las "Oportunidades Perdidas" (solicitudes en mi zona que no acepté o que fueron tomadas por otros), para entender mejor la demanda real y ajustar mi disponibilidad o mi tasa de aceptación de servicios. | **Escenario 1: Carga y Contenido del Widget**<br>• Given el técnico pertenece al grupo Experimental de H2.<br>• When el técnico carga su dashboard principal.<br>• Then el sistema debe mostrar el widget "Métricas de Oportunidad" en la parte superior.<br>• And el widget debe mostrar los datos calculados: "Solicitudes en tu zona (últ. 7 días)" y "Tasa de Aceptación".<br><br>**Escenario 2: Interacción con el Widget**<br>• Given el widget está visible.<br>• When el técnico hace clic en el widget.<br>• Then el sistema debe registrar el evento `metrics_widget_interaction`. | H2 (Retención del Proveedor) |
| **EXP-US-003** | Asignación Persistente a Grupos de Experimento | Como ElectroLink, necesito que cada usuario (Olivia, Alejandro, u otro) sea asignado de forma aleatoria y persistente a un grupo de experimento al iniciar sesión, para que el Test A/B tenga validez y el usuario no cambie de experiencia. | **Escenario 1: Asignación Inicial**<br>• Given un usuario inicia sesión por primera vez.<br>• When el usuario es asignado a un grupo (Control o Experimental) para H1 y/o H2.<br>• Then el sistema debe guardar esta asignación en la base de datos.<br><br>**Escenario 2: Persistencia del Grupo**<br>• Given un usuario que ya ha sido asignado.<br>• When el usuario inicia sesión de nuevo o accede desde otro dispositivo.<br>• Then el sistema debe mostrarle siempre la misma versión (Control o Experimental) a la que fue asignado inicialmente. | Infraestructura (Soporte H1 y H2) |
| **EXP-US-004** | Registro de Eventos Clave para A/B Testing | Como equipo de ElectroLink, quiero que los eventos críticos del experimento (Solicitud de Servicio y Cancelación) registren la propiedad del grupo de experimento, para poder comparar las tasas de conversión y abandono entre el Control y el Experimental. | **Escenario 1: Tracking de Solicitud de Servicio**<br>• Given un propietario hace clic en "Solicitar Servicio".<br>• When el evento `service_request_initiated` es enviado a Google Analytics.<br>• Then el evento debe incluir una propiedad que indique si el propietario estaba en el grupo Control o Experimental de H1.<br><br>**Escenario 2: Tracking de Intento de Cancelación**<br>• Given un técnico hace clic en el botón "Cancelar Suscripción".<br>• When el evento `subscription_cancellation_attempt` es enviado al sistema de tracking.<br>• Then el evento debe incluir una propiedad que indique si el técnico estaba en el grupo Control o Experimental de H2. | Infraestructura (Soporte H1 y H2) |

#### 8.3.2. To-Be Product Backlog

Este es el backlog de las historias de usuario (priorizado) requerido para implementar los experimentos diseñados.

|  Orden| User Story ID | Título                                                 | Story Points (1 / 2 / 3 / 5 / 8) |
|:------| :------------ | :----------------------------------------------------- | :------------------------------- |
| 1     | EXP-US-001    | Perfil con Insignia Verificada y Reseñas Destacadas    | 8                                |
| 2     | EXP-US-002    | Widget de Métricas de Oportunidad para Técnicos       | 8                                |
| 3     | EXP-US-003    | Asignación Persistente a Grupos de Experimento         | 5                                |
| 4     | EXP-US-004    | Registro de Eventos Clave para A/B Testing             | 5                                |


## Conclusiones

Aplicación integral de Domain-Driven Design (DDD) como base estructural del sistema A lo largo de los cuatro sprints, implementamos con rigor el enfoque Domain-Driven Design, lo que nos permitió modelar el sistema en torno a las reglas del negocio y segmentarlo en bounded contexts claramente definidos. Esta estrategia favoreció una solución escalable, mantenible y con bajo acoplamiento, reflejada en la implementación exitosa de los módulos Profiles, IAM, Subscriptions, Monitoring y Service Design and Planning.

Desarrollo completo de la solución con visión modular y centrada en el usuario El sistema final integra perfiles personalizables, control de acceso y autenticación, gestión de suscripciones con beneficios concretos, monitoreo de operaciones y planificación de servicios eléctricos. Cada módulo respondió directamente a una necesidad prioritaria detectada en la investigación inicial, asegurando que la solución tuviera impacto real tanto en usuarios residenciales como en proveedores eléctricos.

Evolución progresiva y consistente en los 4 sprints A lo largo del ciclo de desarrollo, cada sprint abordó objetivos técnicos y funcionales de manera incremental: desde la validación de hipótesis con usuarios hasta el despliegue y prueba de funcionalidades clave. Esta metodología ágil nos permitió iterar rápidamente sobre feedback, ajustar componentes críticos del dominio y entregar una plataforma robusta al finalizar el proyecto.

Trabajo colaborativo y madurez del equipo en entornos reales de ingeniería de software El equipo demostró madurez técnica y organizacional al distribuir responsabilidades de forma eficiente, resolver conflictos de integración y tomar decisiones fundamentadas en el dominio. A medida que el proyecto avanzaba, se fortaleció la sinergia entre los roles de análisis, desarrollo, diseño y pruebas, consolidando un flujo de trabajo productivo y alineado a los objetivos del cliente.

Alineamiento entre descubrimiento de usuario y diseño técnico Las metodologías aplicadas —como entrevistas en profundidad, Lean UX, y Customer Journey Mapping— fueron claves para construir una solución centrada en el usuario. Estas herramientas no solo enriquecieron la comprensión del problema, sino que permitieron traducir insights reales en decisiones técnicas concretas a nivel de entidades, agregados, servicios y eventos de dominio.

Base sólida para la evolución futura del producto en nuevos mercados La arquitectura actual permite escalar la plataforma a nuevas regiones y segmentos con mínima fricción técnica. Además, la implementación por contextos desacoplados favorece la incorporación futura de integraciones externas (pagos, logística, verificación digital) y mecanismos de gobernanza para comunidades de técnicos certificados.

Cumplimiento de los objetivos estratégicos del proyecto ElectroLink finaliza su desarrollo como una solución madura que conecta de forma confiable a usuarios con técnicos certificados y proveedores de componentes, reduciendo significativamente los riesgos de informalidad e ineficiencia en el sector eléctrico. La plataforma logra resolver los principales pain points del mercado inicial, y está lista para ser validada en condiciones reales de uso con métricas claras de éxito.

## Bibliografía

- Conventional Commits. (s.f.). *Conventional commits*. Recuperado el 10 de julio de 2025, de https://www.conventionalcommits.org/

- Google. (s.f.). *Firebase Hosting*. Recuperado el 10 de julio de 2025, de https://firebase.google.com/docs/hosting?hl=es-419

- Google. (s.f.). *Google HTML/CSS style guide*. Recuperado el 10 de julio de 2025, de https://google.github.io/styleguide/htmlcssguide.html

- REST API Tutorial. (s.f.). *What is REST?*. Recuperado el 10 de julio de 2025, de https://www.restapitutorial.com/introduction/whatisrest

- RESTfulAPI.net. (s.f.). *REST API tutorial*. Recuperado el 10 de julio de 2025, de https://restfulapi.net

- UXPressia. (s.f.). *User vs. buyer persona: Differences and free template*. Recuperado el 10 de julio de 2025, de https://uxpressia.com/blog/user-persona-vs-buyer-persona-difference

- W3Schools. (s.f.). *HTML style guide and coding conventions*. Recuperado el 10 de julio de 2025, de https://www.w3schools.com/html/html5_syntax.asp

## Anexos

- Organización GitHub: https://github.com/ElectroLink-Diseno-de-Experimentos
- Repositorio de la Landing Page: https://github.com/ElectroLink-Diseno-de-Experimentos/Landing-Page
- Repositorio Frontend: https://github.com/ElectroLink-Diseno-de-Experimentos/Frontend
- Repositorio Backend: https://github.com/ElectroLink-Diseno-de-Experimentos/Backend
- Repositorio de Pruebas de Integracion (Feature): https://github.com/ElectroLink-Diseno-de-Experimentos/Electrolink-API-Tests
- Landing Page: https://electrolink-diseno-de-experimentos.github.io/Landing-Page/
- Frontend: https://electrolink-195e0.web.app/
- Backend: https://electrolinkv2.onrender.com/swagger-ui/index.html#
