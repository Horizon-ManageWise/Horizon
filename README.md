# Horizon

Product: ManageWise

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

<p align="center">
  <img src="https://res.cloudinary.com/upcbinary/image/upload/v1676924787/ExploraUPC/images/upc_logo_200x200_jao73r.png">
</p>

## Ingenieria de Software

## 5to ciclo

## Desarrollo de Aplicaciones Open Source

### **Sección:** WS53

### **Profesor:** Juan Antonio Flores Moroco

### Informe de Trabajo Final

### "Horizon"

### "ManageWise"

### **Integrantes:**

- Estefano Oscar Jaque Peña - u202225466
- Diego Rolin Acuña Tomas - u202221436
- Jose Antonio Alejo Cardenas - u202122484
- John Telesforo Arevalo Meza - u202117377
- Valentino Sandoval Paiva - u20211a962

### Agosto, 2024

## Registro de Versiones del Informe

## Project Report Collaboration Insights

## Contenido

### Tabla de contenidos

1. [**Capítulo I: Introducción**](#capítulo-i-introducción)
   1. [Startup Profile](#11-startup-profile)
      1. [Descripción de la Startup](#111-descripción-de-la-startup)
      2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   2. [Solution Profile](#12-solution-profile)
      1. [Antecedentes y problemática](#121-antecedentes-y-problemática)
      2. [Lean UX Process](#122-lean-ux-process)
         1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
         3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
         4. [Lean UX Canvas](#1224-lean-ux-canvas)
   3. [Segmentos objetivo](#13-segmentos-objetivo)
2. [**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)
   1. [Competidores](#21-competidores)
      1. [Análisis competitivo](#211-análisis-competitivo)
      2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
   2. [Entrevistas](#22-entrevistas)
      1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
      2. [Registro de entrevistas](#222-registro-de-entrevistas)
      3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
   3. [Needfinding](#23-needfinding)
      1. [User Personas](#231-user-personas)
      2. [User Task Matrix](#232-user-task-matrix)
      3. [User Journey Mapping](#233-user-journey-mapping)
      4. [Empathy Mapping](#234-empathy-mapping)
      5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)
   4. [Ubiquitous Language](#24-ubiquitous-language)
3. [**Capítulo II: Requirements Specification**](#capítulo-iii-requirements-specification)
   1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)
   2. [User Stories](#32-user-stories)
   3. [Impact Mapping](#33-impact-mapping)
   4. [Product Backlog](#34-product-backlog)

## Student Outcome

_ABET – EAC - Student Outcome 3_  
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET - EAC - Student Outcome 3.

| Criterio especifico                                                          | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Conclusiones  |
| :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| 1. Comunica oralmente con efectividad <br>a diferentes rangos de audiencia   | **Estefano Oscar Jaque Peña**<br>TB1: Realice el Lean UX Prolem statements y los assumptions<br> **Diego Rolin Acuña Tomas**<br> TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática" <br>**Jose Antonio Alejo Cardenas:** <br>TB1: "Realice el Lean UX Hypothesis Statements y Lean UX Canvas" <br>**John Telesforo Arevalo Meza**<br> TB1: Realice el Lean UX Canvas y los segmentos objetivos<br>**Valentino Sandoval Paiva** <br>TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática | **TB1:** <br> |
| 2. Comunica por escrito con efectividad <br>a diferentes rangos de audiencia | **Estefano Oscar Jaque Peña**<br>TB1: Realice el Lean UX Prolem statements y los assumptions<br> **Diego Rolin Acuña Tomas**<br> TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática" <br>**Jose Antonio Alejo Cardenas**<br> TB1: "Realice el Lean UX Hypothesis Statements y Lean UX Canvas" <br>**John Telesforo Arevalo Meza**<br> TB1: Realice el Lean UX Canvas y los segmentos objetivos<br>**Valentino Sandoval Paiva** <br>TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática  | **TB1:** <br> |

## Capítulo I: Introducción

### 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Horizon es una startup innovadora creada por estudiantes de la Facultad de Ingeniería de la Universidad Privada de Ciencias Aplicadas (UPC).
Las empresas emergentes en el sector del desarrollo de software enfrentan una serie de desafíos únicos, entre los cuales se destaca la carencia de herramientas eficaces para gestionar proyectos e iniciativas.
Esta falta de recursos puede limitar el crecimiento y la capacidad de estas empresas para competir en un mercado cada vez más exigente.
Con el objetivo de proporcionar un apoyo significativo a estas startups, estamos desarrollando un software que no solo mejorará la eficiencia en la gestión de iniciativas, sino que también fomentará una cultura de innovación y adaptabilidad.
Este software integrará tecnologías avanzadas, como inteligencia artificial, para ofrecer análisis predictivos y automatización de tareas, y bases de datos robustas para una gestión efectiva de la información. Además, nuestro software incluirá características personalizables para adaptarse a las necesidades específicas de cada empresa, permitiendo una integración fluida con sus procesos existentes y facilitando una colaboración más eficiente entre equipos.

Misión:
Nuestra misión es elevar la eficiencia, calidad y rentabilidad de los proyectos en startups de desarrollo de software mediante la optimización de sus procesos de gestión de iniciativas. Buscamos ofrecer soluciones innovadoras que no solo simplifiquen y agilicen los flujos de trabajo, sino que también fomenten la colaboración efectiva y la toma de decisiones basada en datos.
Nuestra misión es no solo ser un proveedor de herramientas de gestión, sino un socio estratégico en el camino hacia el éxito y el crecimiento sostenido de nuestras empresas clientes.

Visión:
Aspiramos a convertirnos en el referente principal en la optimización de la gestión de proyectos para startups de desarrollo de software, siendo reconocidos no solo por nuestras soluciones innovadoras, sino también por nuestra capacidad de transformar y potenciar el éxito de las empresas emergentes. Queremos ser el socio estratégico preferido que permita a las startups no solo alcanzar sus metas, sino superar sus expectativas y mantenerse a la vanguardia en un entorno tecnológico en constante evolución.
Nuestro objetivo es liderar el mercado con herramientas que no sólo aborden las necesidades actuales, sino que también anticipen las tendencias futuras y adapten nuestras soluciones a los cambios del sector. Planeamos desarrollar capacidades adicionales como la integración con plataformas emergentes, el soporte para metodologías ágiles avanzadas y la incorporación de funciones de colaboración global para equipos distribuidos.

### 1.1.2. Perfiles de integrantes del equipo

- Estefano Oscar Jaque Peña - U202225466

| <p align="center"><img src="https://cdn.discordapp.com/attachments/1246609784501833810/1275485196589732011/image.png?ex=66c60fa8&is=66c4be28&hm=28e9a7ace2f1c7416404ba1e95041b745cda9a5046b828c99ca1a5039445b645&"> </p> | Soy Estefano Oscar Jaque Peña, tengo 23 años y soy estudiante de la carrera de Ingeniería de Software,<br> una disciplina enfocada en el diseño, desarrollo y gestión de software para solucionar problemas <br>complejos. Desde temprana edad, he sentido fascinación por la tecnología y he buscado aprender <br>constantemente sobre las últimas tendencias en programación. He ampliado mis conocimientos a <br>través de cursos en Python, SQL, y C++, así como también explorando otros lenguajes de programación <br>por mi cuenta. Además, tengo habilidades en el uso avanzado de Excel para análisis de datos y gestión<br> de información. Mi experiencia trabajando en equipos me ha brindado habilidades de comunicación y <br>colaboración que considero fundamentales para contribuir de manera efectiva a proyectos innovadores<br> en el área de la Ingeniería de Software. |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

- Diego Rolin Acuña Tomas - U202221436

| <p align="center"><img width="3000" height="300" src="https://cdn.discordapp.com/attachments/1257109045723271192/1275266454484291584/1_whatsapp_image_2022_09_10_at_6_21_27_pm.jpeg?ex=66c543f0&is=66c3f270&hm=ff4e77e9d7155359050d176bdbb843afec0163b5a1189920cefca60fce153d40&"> </p> | Soy Diego Rolin Acuña Tomas, tengo 22 años y estoy cursando la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Desde una temprana edad me han facinado las computadoras y como se mostraban en las peliculas los expertos en informatica. Hoy en dia entiendo la importancia de mi disciplina en el mundo y quisiera ser parte de las ventajas que pueden proveer los conocimientos en el campo de la informática y la ciencia de la computación. He llevado cursos para aprender lenguajes como Python, C++ y MATLAB, aprendiendo patrones de algoritmo para mi vida profecional. Tambien conosco los tipos de base de datos, aprendi sql server para la bases de datos relacional y mongo DB para bases de datos no relaciones. Quiero seguir mejorando mis habilidades y especializarme en DataScience y Gestión de proyectos. |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

- Valentino Sandoval Paiva - U20211A962

| <p align="center"><img width="300" height="150" src="https://cdn.discordapp.com/attachments/1246609784501833810/1275484304943616051/Captura_de_pantalla_2024-08-20_102209.png?ex=66c60ed3&is=66c4bd53&hm=93399dd5df3ba222969547f5ace957106ac6fa4db31ec965eff3633c76d4a248&"> </p> | Mi nombre es Valentino Sandoval, tengo 19 años y soy estudiante de la carrera de Ingeniería de Software, cursando el 4to ciclo. Siempre he estado interesado en la tecnología, el software y hardware de las computadoras. Además, me gustan mucho los videojuegos, esto me llevo a decidirme a estudiar esta carrera. |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

- José Antonio Alejo Cárdenas - U202122484

| <p align="center"><img width="3400" src="https://cdn.discordapp.com/attachments/1257109045723271192/1275483107750969374/431736242_1183080929593718_8350965829789705455_n.jpg?ex=66c60db6&is=66c4bc36&hm=474bf1421134dedcd161b88fdedca0785b7ee469488a854a42e817df68a83594&"> </p> | Soy José Alejo Cárdenas tengo 23 años soy estudiante de la carrera de Ingeniería de Software del quinto ciclo. Desde pequeño he sentido facinacion por la tecnologia en general sobretodo por el funcionamiento, desarrollo y proteccion del software. He estudiado lenguajes de programacion (java, python y C++), bases de datos (Microsoft SQL Server y Mongo DB) y Sistemas Operativos (Kali Linux y Windows). Asi mismo, tengo experiencia con hardware a nivel de esamblamiento de equipos y funcionamiento del mismo con sus especificaciones tecnicas. Además, mi constante comunicacion y organizacion durante cualquier trabajo grupal aportara mucho dinamismo al proyecto. Mis principales hobbies son entrenar en el gimnasio, jugar videojuegos con mis amigos y salir a conversar con estos ultimos durante algun almuerzo o cena. Para el proyecto aportare organizacion, comunicacion e inspiracion durante todo el transcurso del mismo. |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

- John Telésforo Arévalo Meza - U202117377

| <p align="center"><img width="700" src="https://cdn.discordapp.com/attachments/1274759574087270442/1275491344412053595/Polish_20240820_112102455.jpg?ex=66c61561&is=66c4c3e1&hm=eda1b481e13860c2872fe384620af2ea0cda95e998b298004745c2692db72b4d&"> </p> | Soy John Arévalo, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Tengo conocimiento en lenguajes de programación como python y c++, y bases de datos como SQLServer y MongoDB. Desde pequeño me sentí atraído por la tecnología, por lo que me decidí a estudiar la carrera, además disfruto de jugar videojuegos con amigos en mi tiempo libre. |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

### 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Actualmente los entornos están caracterizados por una alta competencia e incertidumbre, las organizaciones se enfocan en realizar proyectos de software orientados a objetivos estratégicos.
La gestión de proyectos requiere la aplicación de conocimientos, herramientas, técnicas, métodos y habilidades a las actividades del proyecto para lograr el éxito.
En consecuencia, un project manager capacitado es pieza clave en la competitividad de una empresa.
Sin embargo, aun con sus conocimientos le falta una herramienta que facilite la observación del avance del proyecto que pueda ayudar a reducir los fracasos de los proyectos y mejorar el rendimiento de la organización del proyecto.

###### What?

- _¿Qué problema hay?_

El problema a resolver es la falta de herramientas especializadas en el rubro del desarrollo de software que el PM tiene para facilitar sus responsabilidades. Los problemas clave a solucionar son la falta de planificación, la asignación inadecuada de recursos, seguimiento del progreso de los miembros del equipo, entre otros. Además, debe comunicar sus medidas para solucionar estos problemas y notificar cualquier cambio en el plan o nuevo problema.

- _¿Qué relación tiene el problema con el usuario/cliente?_

Si el PM no puede cumplir con sus responsabilidades, esto puede llevar a plazos atrasados, dificultad para resolver un conflicto y uso ineficiente de la mano de obra. Por ello, una herramienta que permita conceptualizar, implementar y monitorear el proyecto asignado tendrá como consecuencia una menor tasa de fracaso y menor costo, además de un ambiente laboral saludable.

###### When?

- _¿Cuándo sucede el problema?_

El problema ocurre porque el PM no puede hacer un seguimiento continuo de los proyectos o tareas asignadas a cada miembro del equipo, en otras palabras si existe algún retraso o problema y el miembro del equipo no lo comunica el PM no podrá actuar rápidamente.

- _¿Cuándo el cliente necesita el programa?_

El cliente objetivo son los PM, los encargados de un proyecto usarán nuestro programa para registrar las tareas del proyecto y los equipos de trabajo, asignar tareas y plazos, y muchas más herramientas para facilitar su labor. También, será útil en el ciclo de vida del desarrollo pues le permitirá observar de manera continua el desarrollo que aporta cada miembro del equipo y se le notificará cuando una tarea no se cumple o no avanza según lo planeado.

###### Where?

- _¿Dónde el cliente usara el producto?_

Al especializarnos en el desarrollo de software, los usuarios pueden usar nuestro programa en las oficinas de la empresa en la que trabajan o en sus hogares, pues en muchos proyectos de desarrollo de software no es necesario las reuniones presenciales.

- _¿A quién está destinado?_

Hoy en día, las empresas son conscientes del impacto en el éxito o fracaso del PM en un proyecto, y un PM no puede cumplir las expectativas sin herramientas que le permitan planificar, ejecutar y controlar, nuestra aplicación le otorgará todas las herramientas. En consecuencia las organizaciones entienden la necesidad de adquirir nuestro producto para su equipo de trabajo.

###### Who?

- _¿Quiénes van a involucrarse con nuestra aplicación?_

Los involucrados en el uso de nuestra aplicación son los miembros de trabajo y el director del proyecto, todos los involucrados deben usarlo para mandar sus avances, resultados de testeo o incluso mensajes, todo para que el equipo este comunicado a lo largo del ciclo de vida del proyecto.

- _¿Quiénes son afectados por el problema?_

El problema afecta a todos los miembros de la organización, pues cuando no puedes cumplir un proyecto genera retrasos, pérdidas monetarias, despidos, pérdida de la confianza en la empresa, entre otros. Por supuesto, las consecuencias dependen de la importancia del proyecto, sin embargo para todos la probabilidad de éxito aumenta cuando el PM puede cumplir con su deber con más eficiencia.

- _¿Quién utilizará este producto?_

Los miembros del equipo de trabajo del proyecto para ingresar sus avances o cambios, para notificar que cumplieron sus tareas, para mandar notificaciones sobre problemas encontrados o errores sin solución aparente, entre otros. Los líderes de los equipos o el gerente del proyecto podrán ver el avance del proyecto, recibir notificaciones si una tarea no se cumplió en sus plazos, la eficiencia de los miembros del equipo y comunicar al equipo los cambios de responsabilidades para responder a un problema.

###### Why?

- _¿Por qué ocurre el problema?_

Queremos solucionar la escasez de programas para la gestión de proyectos especializados en el desarrollo de software. En la actualidad, las aplicaciones de gestión de proyectos no están especializadas, por lo que la mayoría no tiene las herramientas que le permitirían al PM conocer con detalle cómo los miembros de su equipo están programando. Aspectos como el lenguaje de programación, frameworks, base de datos relacional o no relacional, los resultados del testeo con detalle, entre otros, son información muy necesaria para el trabajo de equipo.

- _¿Por qué los clientes elegirían utilizar nuestro producto?_

Lo usan antes, durante y después del Ciclo de Vida del Desarrollo de Software (SDLC). Lo usarán antes para planear las tareas del proyecto, definir equipos de trabajo, el uso de lenguajes de programación y frameworks, entre otros. Durante el SDLC, los trabajadores pueden mandar su trabajo y los supervisores pueden tomar medidas para cualquier retraso o problema con la ruta de tareas. Después del SDLC, la empresa podrá ver la información sobre el desempeño de cada trabajador y evaluarlos.

- _¿Por qué las personas estarán motivadas a usar nuestra aplicación?_

Las empresas conocen la importancia de un project manager en el ciclo de vida del desarrollo de software, pero también conocen el costo que requeriría contratar muchos para un solo proyecto. Las herramientas adecuadas permitirían que un número reducido de PM pueden cumplir sus deberes de igual o incluso más eficiente que muchos. En otras palabras, con la herramienta de gestión de proyectos especializada en desarrollo de software permitirá bajar costos y mantener la probabilidad de éxito del proyecto,e incluso podría incluso aumentarla.

###### Who?

- _¿Cómo nos descubren nuestros clientes?_

Nuestros clientes pueden conocer nuestra marca a través de una amplia variedad de estrategias publicitarias en línea, que incluyen anuncios en redes sociales, banners en sitios web relevantes y campañas de email marketing. Además, la recomendación de empresas que ya han experimentado la calidad de nuestro producto y se han beneficiado de él jugará un papel crucial en la difusión de nuestra marca mediante el boca a boca.

- _¿Cómo pueden los clientes acceder a nuestro contenido?_

El acceso a nuestro contenido será muy sencillo y flexible. Los clientes podrán conectarse a través de cualquier dispositivo móvil, ya sea un teléfono inteligente, una tablet, o una laptop. Además, nuestra plataforma será completamente funcional en computadoras de escritorio y portátiles, asegurando así una experiencia de usuario fluida y accesible desde múltiples tipos de dispositivos.

- _¿Qué factores llevan a los clientes a elegirnos?_

Los clientes se sentirán atraídos hacia nuestra solución por la facilidad que ofrecemos en la gestión de proyectos. Nuestra herramienta está diseñada para centralizar toda la información relevante, facilitando su acceso para todos los miembros del equipo y partes interesadas en el proyecto. Al proporcionar una plataforma que mejora la coordinación y transparencia, permitimos a los clientes optimizar su flujo de trabajo y mejorar la eficiencia en el desarrollo de proyectos, lo que les lleva a elegirnos como su proveedor preferido.

###### How much?

A lo largo de la vida de un proyecto, es común observar diferentes etapas que reflejan su estado de salud o dificultades. Cuando surgen problemas inesperados, es fundamental realizar un diagnóstico preciso para identificar las causas subyacentes y desarrollar soluciones adecuadas. Los problemas frecuentes que pueden surgir incluyen una comprensión deficiente de los objetivos del proyecto, la falta de un plan detallado y claro, problemas en el control y la comunicación, una gestión ineficaz de los cambios y de las partes interesadas, y una falta de motivación entre los miembros del equipo.

Además, es importante considerar otros factores que pueden afectar la salud del proyecto, como la falta de recursos adecuados, la resistencia al cambio, y la falta de alineación entre los miembros del equipo y los objetivos del proyecto. También puede haber problemas con la integración de nuevas tecnologías o herramientas, así como dificultades en la adaptación a condiciones cambiantes del mercado o del entorno empresarial. Abordar estos aspectos de manera proactiva y con una estrategia bien definida puede ayudar a mantener el proyecto en el camino correcto y garantizar su éxito a largo plazo.

### 1.2.2. Lean UX Process

El proceso Lean UX se adapta especialmente bien a startups como Horizon que buscan crear soluciones innovadoras y efectivas en el mercado. Este enfoque se caracteriza por su agilidad y centrado en el usuario, lo que significa que estamos constantemente buscando validar nuestras ideas y prototipos con los usuarios para garantizar que estamos abordando sus necesidades de manera adecuada.

### 1.2.2.1. Lean UX Problem Statements

Después de analizar la problemática y los factores que la ocasionan, podemos tener un panorama de cómo solucionar la necesidad del usuario declarando supuestos, lo cual corresponde al siguiente paso de la Lean UX. Por ello, es necesario tener un conocimiento previo de las empresas que tienen características similares a las nuestras y cómo estas se han desarrollado con el paso del tiempo.
En primer lugar, hablamos de la herramienta Trello, creada por el ingeniero y escritor Avram Joel Spolsky, que su objetivo es proveer una herramienta para la organización de la información. Esta plataforma está optimizada para hacer más sencillas las tareas de los equipos de trabajo.
En segundo lugar, tenemos la herramienta Jira Software, fue desarrollada por la empresa australiana Atlassian. Está es similar a las funciones de Trello, pero lo resaltante es la compatibilidad con cualquier metodología ágil, ya sea Scrum, Kanban o la tuya propia.

### 1.2.2.2. Lean UX Assumptions

Assumptions:

1. Creo que mis clientes necesitan una forma más eficiente de gestionar proyectos e iniciativas dentro de sus empresas emergentes de desarrollo de software.

2. Estas necesidades se pueden resolver con una herramienta de gestión de proyectos ágil y adaptable que se integre fácilmente con los flujos de trabajo existentes.

3. Mis clientes iniciales serán startups de tecnología que buscan mejorar la eficiencia y la colaboración en sus equipos de desarrollo.

4. El valor que un cliente quiere de mi servicio que requieren los usuarios es una plataforma intuitiva que les permita planificar, seguir y adaptarse rápidamente a los cambios en sus proyectos.

5. El cliente también puede obtener estos beneficios adicionales en donde implementaremos integraciones con herramientas populares de desarrollo de software, como repositorios de código y herramientas de colaboración.

6. Voy a adquirir la mayoría de mis clientes a través de estrategias de marketing digital dirigidas a startups de tecnología y a través de referencias de clientes satisfechos.

7. Haré dinero a través de un modelo de suscripción mensual o anual, ofreciendo diferentes niveles de funcionalidad según las necesidades del cliente.

8. Mi competencia principal en el mercado serán Trello, Jira Software y Asana.

9. Los venceremos debido a nuestra facilidad de uso, integraciones flexibles y enfoque en las necesidades específicas de las empresas emergentes de desarrollo de software.

10. Mi mayor riesgo de producto es la falta de adopción por parte de los equipos de desarrollo, debido a la resistencia al cambio o a la preferencia por soluciones existentes.

Business Outcomes:

- Optimizar la eficiencia operativa y la colaboración dentro de equipos de desarrollo de software.
- Reducción de obstáculos relacionados con la falta de herramientas de gestión de proyectos e iniciativas.

User Outcomes:

1. ¿Quién es el usuario?  
   Los usuarios son gerentes de proyectos de software, equipos de desarrollo de software y líderes empresariales de empresas emergentes en el ámbito del desarrollo de software.

2. ¿Dónde encaja nuestra empresa en su trabajo o vida?  
   Nuestra empresa se posiciona como proveedora de herramientas de gestión de proyectos e iniciativas para facilitar el desarrollo de software en empresas emergentes.

3. ¿Qué problemas tiene nuestra empresa?  
   Nos enfrentamos a la falta de herramientas especializadas que se adapten a las necesidades únicas de las empresas emergentes de desarrollo de software, lo que dificulta la gestión eficiente de proyectos y recursos.

4. ¿Cuándo y cómo es nuestra empresa?  
   Nuestra empresa está en una etapa inicial, ofreciendo soluciones ágiles y flexibles que se ajustan a las demandas cambiantes del mercado de desarrollo de software.

5. ¿Qué características son importantes?  
   Las características importantes incluyen una interfaz intuitiva y fácil de usar, capacidades para la gestión de tareas y asignación de recursos, así como integraciones con herramientas populares de desarrollo de software.

6. ¿Cómo debe verse nuestra empresa y comportarse?  
   Nuestra empresa debe presentarse como un aliado confiable que simplifica y optimiza la gestión de proyectos de desarrollo de software, siendo receptiva a las sugerencias de los usuarios y comprometida con la innovación y la mejora continua.

### 1.2.2.3. Lean UX Hypothesis Statements

- Hypothesis 1:

Creemos que la implementación de un software que haga uso de inteligencia artificial y bases de datos, inclinado a mejorar gestión de actividades en startups de desarrollo de software, incrementará notablemente la eficiencia operativa y la rentabilidad de los proyectos.
Sabremos que esto es cierto cuando observemos una reducción del 20% en los retrasos en la entrega de proyectos y una mejora del 30% en el uso eficiente de recursos.

- Hypothesis 2:

Creemos que brindar herramientas adecuadas para la gestión eficaz de proyectos e iniciativas en startups de desarrollo de software permitirá superar obstáculos y dificultades relacionados con plazos y recursos limitados.
Sabremos que hemos tenido exito cuando los usuarios informen un incremento del 35% en la claridad y seguimiento de tareas, junto con una mejora del 18% en la satisfacción del equipo respecto a la gestión de proyectos.

- Hypothesis 3:

Creemos que la implementacion de un software integral que simplifique el seguimiento y la gestión de proyectos en startups de desarrollo de software mejorará el trabajo en equipo y la suficiencia de entrega de productos a tiempo.
Sabremos que estamos en lo cierto cuando veamos con una reducción del 25% en los costos asociados a retrasos y una mejora del 15% en la capacidad de adaptación a cambios en los requisitos.

- Hypothesis 4:

Creemos que al brindar una herramienta tecnológica que favorezca la gestión de proyectos en startups de desarrollo de software, incrementaremos la capacidad de produccion del equipo y la capacidad de adaptarse rápidamente a cambios en los requisitos del proyecto.
Sabremos que hemos tenido éxito cuando veamos un aumento del 22% en la agilidad y una reduccion del 10% de tiempo de respuesta del equipo ante nuevas solicitudes y una reducción del 10% en los tiempos de comunicación y coordinación entre equipos.

- Hypothesis 5:

Creemos que al proporcionar una solución innovadora basada en inteligencia artificial y bases de datos para la gestión de proyectos, mejoraremos la calidad de los entregables y la satisfacción del cliente en startups de desarrollo de software.
Sabremos que hemos tenido exito cuando observemos un incremento del 20% en las calificaciones de satisfacción del cliente y una disminución del 15% en los errores de las entregas.

- Hypothesis 6:

Creemos que la integración de herramientas de seguimiento y análisis de datos en nuestro software aumentará la transparencia y visibilidad del desarrollo de los proyectos para los líderes de equipo y supervisores en startups de desarrollo de software.
Sabremos que estamos en lo cierto cuando veamos un aumento del 25% en la capacidad de los líderes para tomar decisiones informadas basadas en datos y una mejora del 20% en la precisión de los estimados de tiempo y optimizacion de recursos.

- Hypothesis 7:

Creemos que al ofrecer una plataforma de facil uso y acceso desde múltiples dispositivos, aumentaremos la aceptacion y la eficacia del software por parte de los equipos de trabajo en startups de desarrollo de software.
Sabremos que hemos tenido exito cuando observemos en un incremento del 30% en la tasa de aceptacion del software y una mejora del 20% en la colaboración y participación entre equipos.

- Hypothesis 8:

Creemos que la implementación de un sistema automatizado de seguimiento de proyectos disminuira la carga administrativa y permitirá que los equipos se concentren en actividades más productivas durante el desarrollo de software.
Sabremos que hemos tenido exito cuando veamos una reducción del 10% en el tiempo destinado a tareas administrativas y una mejora del 22% en el tiempo invertido en actividades de desarrollo y despliegue de software.

- Hypothesis 9:

Creemos que al proveer herramientas de análisis predictivo para la gestionar riesgos, ayudaremos a aminorizar problemas potenciales y a mejorar la capacidad de anticipación en startups de desarrollo de software.
Sabremos que hemos tenido éxito cuando veamos una reducción del 12% en los riesgos identificados durante los proyectos y un incremento del 30% en la capacidad de respuesta ante riesgos críticos.

- Hypothesis 10:

Creemos que posibilitar la colaboración remota y la comunicación en tiempo real entre los equipo de trabajo incrementará la eficiencia operativa y la flexibilidad laboral en startups de desarrollo de software.
Sabremos que hemos tenido exito cuando veamos un aumento del 35% en la productividad de los equipos de trabajo y una reducción del 15% en los tiempos de respuesta al solucionar problemas y organizar actividades entre ubicaciones distantes.

### 1.2.2.4. Lean UX Canvas

| Sección                                                                                             | Contenido                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Problem**                                                                                | La falta de una solución completa para la gestión de proyectos puede resultar en demoras en las entregas, sobrepasar <br> los presupuestos y disminuir la satisfacción del cliente. <br> Gestión ineficiente de proyectos e iniciativas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Business Outcomes**                                                                               | Aumentar la productividad de la empresa. <br> Reducir el tiempo desde la planificación del proyecto hasta el lanzamiento del producto final.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Users and Customers**                                                                             | Identificación de los diferentes tipos de usuarios y clientes que interactuarán con el producto, sus necesidades, comportamientos y características.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **User Benefits**                                                                                   | Optimización del tiempo y recursos <br> Comunicación mejorada <br> Productos y servicios de excelente calidad                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Solution Ideas**                                                                                  | Facilitar la comunicación y colaboración entre equipos mediante la integración de herramientas de mensajería instantánea, <br> como Slack o Microsoft Teams, directamente en la plataforma de gestión de proyectos. <br> Establecimiento de objetivos claros y alcanzables.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Hypotheses**                                                                                      | Creemos que la implementación de un software que haga uso de inteligencia artificial y bases de datos, inclinado a mejorar gestión de actividades en <br> startups de desarrollo de software, incrementará notablemente la eficiencia operativa y la rentabilidad de los proyectos. Sabremos que esto es cierto cuando observemos una reducción del 20% en los retrasos en la entrega de proyectos y una mejora del 30% en el uso eficiente de recursos. <br> Creemos que brindar herramientas adecuadas para la gestión eficaz de proyectos e iniciativas en startups de desarrollo de software permitirá superar obstáculos <br> y dificultades relacionados con plazos y recursos limitados. Sabremos que hemos tenido exito cuando los usuarios informen un incremento del 35% en la claridad y seguimiento de tareas, junto con una mejora del 18% en la satisfacción del equipo respecto a la gestión de proyectos. |
| **What's the most important <br> thing we need to learn first?**                                    | Conocer las expectativas y deseos de los clientes. <br> Identificar los problemas que los clientes puedan enfrentar. <br> Descubrir qué actualizaciones esperan los futuros usuarios para mejorar la app.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **What's the least amount of <br> work we need to do to learn <br> the next most important thing?** | Realizar entrevistas para explorar cómo abordar el tema. <br> Tener como referencia una app similar que tenga algunas funciones, pero no idénticas. <br> Realizar encuestas a personas con experiencia y conocimientos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

### 1.3. Segmentos objetivo

**Lider o gerente de empresa de desarrollo de software en crecimiento:**  
Descripción: Empresas desde startups innovadoras hasta organizaciones establecidas con rápido crecimiento. Se distinguen por su necesidad de herramientas que optimicen sus procesos de desarrollo y gestión de proyectos.  
Necesidades: Buscan soluciones que les permitan gestionar proyectos de manera eficiente y mejorar la coordinación del equipo.  
Aspiraciones: Quieren liderar en su sector, innovar constantemente, y ofrecer productos de software de alta calidad.

**Equipo de Desarrollo de Software:**  
Descripción: Equipos dentro de empresas de TI dedicados a la creación y mejora de software.
Necesidades: Necesitan plataformas que faciliten la colaboración, gestionen el flujo de trabajo, y ofrezcan visibilidad sobre el progreso del mismo. Además de poder supervisar el trabajo de todos los miembros.  
Aspiraciones: Aspiran a culminar el proyecto de la mejor forma y en el menor tiempo posible.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

Wrike: Wrike es una plataforma de gestión de proyectos colaborativa que permite a los equipos planificar, rastrear y gestionar proyectos con alta eficiencia.

Trello:Trello es una herramienta de gestión de proyectos basada en tableros que permite organizar tareas de manera visual y sencilla.

ClickUp: ClickUp es una plataforma todo-en-uno de gestión de proyectos que incluye desde tareas simples hasta colaboración avanzada y gestión de tiempo.

### 2.1.1. Análisis competitivo

Competitive Analysis Landscape

¿Por qué llevar a cabo este análisis?  
Para poder tener un análisis completo sobre nuestro modelo de negocio además de poder comprender a nuestros competidores.

| Nombre de <br>los Startups <br> o Empresas |                                                               | Nuestra startup                                                                                                                                                                                                                                                  | Competidor 1                                                                                                                                                                                                                                                                                                     | Competidor 2                                                                                                                                                                                       | Competidor 3                                                                                                                                                                                                      |
| ------------------------------------------ | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Perfil                                     | Overview                                                      | Horizon                                                                                                                                                                                                                                                          | Wrike                                                                                                                                                                                                                                                                                                            | Trello                                                                                                                                                                                             | ClickUp                                                                                                                                                                                                           |
|                                            | Ventaja competitiva:<br>¿Qué valor ofrece<br> a los clientes? | Proporciona una interfaz intuitiva <br>y fácil de usar, en la que Lo usan<br> antes, durante y después del<br> Ciclo de Vida del Desarrollo de<br> Software.                                                                                                     | ofrece análisis predictivos,<br> automatización avanzada y <br>herramientas de colaboración <br>que permiten a los equipos<br> mejorar la productividad y <br>la visibilidad del proyecto<br> en tiempo real.                                                                                                    | Proporciona una interfaz <br>intuitiva y fácil de usar,<br> ideal para equipos pequeños<br> y startups que buscan <br>simplicidad en la gestión <br>de tareas.                                     | Proporciona una solución <br>altamente personalizable <br>que puede adaptarse a <br>diferentes necesidades <br>empresariales, integrando <br>gestión de tareas, tiempo <br>y recursos en una sola <br>plataforma. |
| Perfil de Marketing                        | Mercado Objetivo                                              | Startups de tecnología que buscan<br> mejorar la eficiencia y la colaboración<br> en sus equipos de desarrollo                                                                                                                                                   | Empresas medianas a grandes,<br> así como equipos de proyectos <br>complejos que requieren <br>integración y colaboración <br>avanzadas.                                                                                                                                                                         | Equipos pequeños, startups<br> y empresas que necesitan <br>una herramienta <br>de gestión de proyectos <br>visual y simple.                                                                       | Startups, pequeñas y medianas <br>empresas que buscan una <br>herramienta flexible y completa <br>para la gestión de proyectos.                                                                                   |
|                                            | Estrategias de Marketing                                      | Uso de marketing digital dirigido<br> a comunidades tecnológicas, con <br> pruebas gratuitas y asociaciones<br> estratégicas                                                                                                                                     | Wrike se posiciona como una <br>herramienta robusta y flexible <br>para equipos que necesitan <br>mejorar la eficiencia operativa <br>y la gestión de proyectos. <br>Su estrategia incluye <br>demostraciones personalizadas <br>y un enfoque en las <br>integraciones con otras <br>herramientas empresariales. | Se enfoca en la simplicidad <br>y la accesibilidad, <br>promocionando su facilidad <br>de uso y la posibilidad de <br>integrarse con herramientas <br>populares como Slack y <br>Google Workspace. | Se posiciona como una alternativa<br> más económica y todo-en-uno a <br>las herramientas tradicionales de <br>gestión de proyectos, con un <br>fuerte enfoque en la personalización<br> y la escalabilidad.       |
| Perfil del producto                        | Productos y servicios                                         | Plataforma que ofrece un sistema <br>de colaboración en tiempo real <br>con características como edición <br>simultánea de documentos y un <br>espacio de trabajo unificado,<br> permitiendo a los equipos trabajar<br> de manera más eficiente y<br> conectada. | Ofrece un conjunto completo de <br>herramientas de gestión de <br>proyectos, desde la planificación <br>hasta la ejecución, incluyendo <br>paneles de control, cronogramas <br>de Gantt y flujos de trabajo<br> automatizados.                                                                                   | Ofrece tableros Kanban para<br> la gestión de proyectos, con<br> opciones de listas de tareas,<br> etiquetas y archivos adjuntos                                                                   | Ofrece una amplia gama de <br>herramientas para la gestión de <br>tareas, seguimiento del tiempo, <br>automatización de flujos de <br>trabajo y colaboración en equipo.                                           |
|                                            | Precios y Costos                                              | Planes escalables, comenzando <br>con versiones gratuitas para<br> atraer startups en etapas iniciales                                                                                                                                                           | Sus planes varían desde versiones <br>gratuitas limitadas hasta <br>suscripciones empresariales <br>premium, comenzando en<br>aproximadamente $9.80 por<br> usuario/mes.                                                                                                                                         | Ofrece una versión gratuita<br> con limitaciones y planes <br>premium que comienzan en <br>$5 por usuario/mes.                                                                                     | Plan gratuito robusto y planes <br>pagos que comienzan en $5 <br>por usuario/mes.                                                                                                                                 |
|                                            | Canales de distribución <br>(Web y/o Móvil)                   | La plataforma se ofrecerá <br>como un servicio web basado<br> en la nube (SaaS), accesible<br> desde cualquier navegador, <br>con integraciones clave como <br>Slack y Google Workspace.                                                                         | Se distribuye principalmente a <br>través de su sitio web oficial,<br> con soporte adicional en <br>aplicaciones móviles y a través<br> de integraciones con plataformas<br> como Microsoft Teams y <br>Salesforce.                                                                                              | Distribuido principalmente a <br>través de su sitio web oficial,<br> y también disponible en <br>aplicaciones móviles para iOS <br>y Android.                                                      | Se distribuye a través de su<br> sitio web y tiene aplicaciones<br> para dispositivos móviles,<br> además de extensiones <br>para navegadores.                                                                    |
| Análisis SWOT                              | Fortalezas                                                    | Innovación en colaboración<br> en tiempo real, enfoque en startups.                                                                                                                                                                                              | Funcionalidad robusta,<br> integración con otras herramientas<br> empresariales, análisis predictivo.                                                                                                                                                                                                            | Interfaz intuitiva, amplia <br>accesibilidad, integración<br> con múltiples herramientas.                                                                                                          | Altamente personalizable,<br> excelente relación calidad-precio,<br> fuerte integración.                                                                                                                          |
|                                            | Debilidades                                                   | Base de usuarios inicial limitada.                                                                                                                                                                                                                               | Curva de aprendizaje<br> pronunciada para nuevos usuarios.                                                                                                                                                                                                                                                       | Limitaciones en funciones <br>avanzadas para la gestión<br> de proyectos complejos.                                                                                                                | Puede ser abrumador para <br>usuarios nuevos debido<br> a su vasta cantidad de funciones.                                                                                                                         |
|                                            | Oportunidades                                                 | Expansión en mercados emergentes <br>y nuevas tecnologías.                                                                                                                                                                                                       | Expansión en mercados emergentes,<br> desarrollo de nuevas <br> funcionalidades de IA.                                                                                                                                                                                                                           | Expansión de integraciones <br>y nuevas funcionalidades<br> para grandes equipos.                                                                                                                  | Expansión en mercados globales, <br>mejoras continuas en <br>automatización y AI.                                                                                                                                 |
|                                            | Amenazas                                                      | Competencia con herramientas <br>más establecidas y la necesidad <br>de mantenerse al día con la<br> evolución tecnológica.                                                                                                                                      | Competencia creciente con <br>herramientas más accesibles <br>y económicas.                                                                                                                                                                                                                                      | Competencia con<br> herramientas que ofrecen <br>más funciones por un costo<br> similar.                                                                                                           | La competencia con<br> herramientas establecidas <br>que tienen una base de<br> usuarios leal.                                                                                                                    |

### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas

En esta sección del informe se realizará el diseño, registro y análisis de las entrevistas de nuestros segmentos objetivos

### 2.2.1. Diseño de entrevistas

Segmentos encontrados:

- Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento

- Equipo de Desarrollo de Software

Antes de poder realizar las entrevistas, consideramos prudente poder concretar un análisis previo para poder realizar las entrevistas de una mejor manera. Es por ello, que para cada uno de nuestros segmentos proponemos estas preguntas para poder conocer un poco más sobre nuestro público objetivo.

Preguntas :
preguntas ordenadas para entrevistar a los dos segmentos objetivos de la startup "Horizon":

### Segmento: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento
**Principales:**
1. **Introducción al Rol**: ¿Podría describir su rol en la empresa y las principales responsabilidades que tiene en el área de desarrollo de software?
2. **Contexto Empresarial**: ¿Cuál es el enfoque principal de su empresa en términos de productos o servicios de software?
3. **Crecimiento y Desafíos**: ¿Cuáles son los mayores desafíos que enfrenta su empresa actualmente en términos de crecimiento y gestión de proyectos?
4. **Experiencias Pasadas**: ¿Ha tenido alguna experiencia negativa con las herramientas actuales de gestión de proyectos que utiliza?
5. **Necesidades Específicas**: ¿Qué características considera esenciales en una herramienta de gestión de proyectos para apoyar el crecimiento y la eficiencia de su equipo?
6. **Impacto de la Innovación**: ¿Qué tan importante es para usted que la herramienta de gestión de proyectos incorpore tecnologías emergentes como la inteligencia artificial?
7. **Colaboración y Comunicación**: ¿Cómo maneja actualmente la colaboración y la comunicación entre los diferentes equipos dentro de su empresa?
8. **Evaluación de Soluciones Actuales**: ¿Siente que las herramientas actuales limitan su capacidad para innovar y liderar en su sector?
9. **Visión Futura**: ¿Cómo imagina la evolución de sus procesos de gestión de proyectos en los próximos 5 años?
10. **Interés en Nuevas Soluciones**: ¿Qué tan abierto estaría a explorar y adoptar una nueva herramienta de gestión de proyectos que ofrezca características avanzadas y personalizables?
11. **Experiencia con Proveedores Externos**: ¿Cuál ha sido su experiencia al trabajar con proveedores externos de soluciones de software? ¿Qué busca en un socio estratégico?
12. **Expectativas a Largo Plazo**: ¿Qué expectativas tendría para una colaboración a largo plazo con una empresa que ofrezca soluciones de gestión de proyectos?
13. **Adaptabilidad y Personalización**: ¿Qué tan importante es para usted que una herramienta de gestión se adapte específicamente a las necesidades y procesos de su empresa?
14. **Consideraciones de Seguridad**: ¿Qué preocupaciones o requisitos de seguridad tiene al implementar nuevas herramientas de software?
15. **Disposición a Colaborar**: Si encuentra que una herramienta cumple con sus expectativas, ¿estaría dispuesto a colaborar con la empresa desarrolladora para ajustar la herramienta a las necesidades emergentes de su equipo?

**Complementarias:**

1. **Integración con Herramientas Existentes**: ¿Qué tan importante es para usted que la nueva herramienta de gestión de proyectos se integre sin problemas con las herramientas de software que ya utiliza su equipo?
2. **Medición del Éxito del Proyecto**: ¿Cuáles son los indicadores clave que utiliza para medir el éxito de un proyecto? ¿Cómo una nueva herramienta podría ayudar a mejorar estos indicadores?
3. **Gestión de Riesgos**: ¿Cómo maneja actualmente los riesgos en los proyectos de desarrollo de software? ¿Qué características le gustaría ver en una herramienta de gestión para facilitar este proceso?
4. **Personalización de Flujos de Trabajo**: ¿Qué tan crucial es para usted la capacidad de personalizar los flujos de trabajo dentro de una herramienta de gestión de proyectos?
5. **Soporte y Actualizaciones**: ¿Qué expectativas tiene respecto al soporte técnico y la frecuencia de actualizaciones de una herramienta de gestión de proyectos?

### Segmento: Equipo de Desarrollo de Software
**Principales:**
1. **Introducción al Rol**: ¿Podría compartirnos un poco sobre su rol en el equipo de desarrollo y las tareas diarias que realiza?
2. **Contexto del Equipo**: ¿Cómo describiría la estructura de su equipo y el tipo de proyectos en los que trabajan habitualmente?
3. **Desafíos en el Desarrollo**: ¿Cuáles son los principales desafíos que enfrenta su equipo en la gestión del flujo de trabajo y la colaboración?
4. **Experiencias Pasadas**: ¿Han tenido alguna experiencia negativa con las herramientas actuales que utilizan para la gestión de proyectos?
5. **Necesidades Específicas**: ¿Qué funcionalidades cree que le facilitarían a su equipo la colaboración y la gestión del trabajo diario?
6. **Impacto en la Productividad**: ¿Cómo afecta la falta de herramientas adecuadas en la eficiencia y productividad del equipo?
7. **Visibilidad y Supervisión**: ¿Qué tan importante es para su equipo tener visibilidad sobre el progreso de los proyectos y el trabajo de cada miembro?
8. **Adopción de Nuevas Tecnologías**: ¿Qué tan abiertos están a la idea de incorporar tecnologías emergentes, como la inteligencia artificial, en las herramientas de gestión?
9. **Satisfacción con Soluciones Actuales**: ¿Sienten que las herramientas actuales limitan su capacidad de entregar proyectos de alta calidad en tiempo y forma?
10. **Visión Futura**: ¿Cómo imagina que podrían mejorar los procesos de desarrollo con una herramienta que optimice la gestión y la colaboración?
11. **Evaluación de Nuevas Soluciones**: ¿Qué factores considera cruciales al evaluar una nueva herramienta de gestión para su equipo?
12. **Experiencia con Proveedores Externos**: ¿Han trabajado anteriormente con proveedores de herramientas de software? ¿Cómo fue esa experiencia?
13. **Expectativas a Largo Plazo**: ¿Qué espera de una colaboración a largo plazo con un proveedor de soluciones de gestión de proyectos?
14. **Personalización y Flexibilidad**: ¿Qué tan importante es para su equipo que una herramienta de gestión sea flexible y personalizable según sus necesidades?
15. **Disposición a Adoptar Nuevas Herramientas**: Si una nueva herramienta satisface las necesidades del equipo, ¿estaría dispuesto a adoptarla y colaborar con la empresa desarrolladora para su mejora continua?

**Complementarias:**

1. **Interfaz de Usuario**: ¿Qué tan importante es para usted que la interfaz de la herramienta de gestión sea intuitiva y fácil de usar? ¿Cómo influiría esto en la adopción por parte del equipo?
2. **Colaboración entre Equipos**: ¿Cómo podría una nueva herramienta de gestión mejorar la colaboración no solo dentro de su equipo, sino también con otros departamentos de la empresa?
3. **Manejo de Prioridades**: ¿Cómo maneja actualmente su equipo las prioridades de tareas y proyectos? ¿Qué funcionalidades en una herramienta de gestión podrían facilitar este proceso?
4. **Capacitación y Adaptación**: ¿Qué tan fácil o difícil le resulta a su equipo adaptarse a nuevas herramientas? ¿Qué tipo de soporte o capacitación considera necesario para una transición exitosa?
5. **Retroalimentación Continua**: ¿Cómo se maneja actualmente la retroalimentación dentro del equipo? ¿Qué tan útil sería una herramienta que facilite la retroalimentación continua sobre el progreso y la calidad del trabajo?

Estas preguntas están diseñadas para llevar la conversación de manera lógica y ordenada, desde la comprensión del rol y desafíos actuales hasta la exploración de futuras colaboraciones y expectativas.

### 2.2.2. Registro de entrevistas

#### Segmento 1: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento

2.  Entrevista 2: <br>
    Datos del entrevistado <br>
    Nombre: María<br>
    Apellidos: Gutiérrez<br>
    Edad: 26 <br>
    Distrito: San Isidro <br>

![Foto de entrevista](https://cdn.discordapp.com/attachments/1257109045723271192/1277323905102643262/image.png?ex=66ccc016&is=66cb6e96&hm=d40e669ac1a0dc296f2b6c9b8b2c106b6bb6e2b70f61e5970b8596d42e7d973d&)

URL: [Link de entrevista](https://drive.google.com/file/d/1URH3QIgHteG1cNFRdPeFrunflBu3zA8j/view?usp=sharing "Entrevista 2")

Inicio: 0:18<br>
Duracion: 6:17

Resumen:<br>
La entrevista con María nos comenta que en su trabajo como líder de proyecto su principal responsabilidad es monitorear todas las operaciones y gestionarlas para lograr el óptimo desarrollo. Considera que las empresas deben empezar a utilizar nuevos programas para la gestión de proyecto, pues las que usan están quedando obsoletas. También nos cuenta de la importancia de que este nuevo programa debe ser intuitiva y fácil de usar, además de ser adaptable para cualquier dispositivo con acceso a internet. Nos comenta su interés de la IA en estos programas está relacionada con todos los logros que han logrado y que ella misma también usa cuando trabaja. Con su experiencia resalta que debe ser poner atención cuando busques una empresa que te ofrezca este producto, es importante que el software pueda adaptarse a sus necesidades y tenga la seguridad de que protegerá sus datos.

3.  Entrevista 3: <br>
    Datos del entrevistado <br>
    Nombre: Nora <br>
    Apellidos: Castro Manrique<br>
    Edad: 42 <br>
    Distrito: Pueblo Libre <br>

![Foto de entrevista](https://cdn.discordapp.com/attachments/1274759574087270442/1277138646398537790/image.png?ex=66cc138d&is=66cac20d&hm=9556920f3d0a0a1a265a357130bf8f88e6490ba54ab2eab73fc697ed90068d4d&)

URL: [Link de entrevista](https://drive.google.com/file/d/11xswJuEZQy51WRqAmZDu0KfjyF-6rV-F/view?usp=sharing "Entrevista 3")

Inicio: 0:40<br>
Duracion: 5:39

Resumen:<br>
La entrevista con Nora reveló aspectos importantes sobre la gestión y flujo de trabajo. Se destacó que el trabajo en equipo es fundamental para el éxito de un proyecto, y que contar con herramientas de gestión y seguimiento efectivas es crucial para mantener la coordinación y el progreso del equipo. Además, se considera que, tecnologías emergentes como la inteligencia artificial serían de mucha ayuda. En un futuro, se espera que este tipo de tecnologías sumadas a herramientas existentes puedan ayudar a su adaptación para diferentes modelos de negocio y a agilizar el trabajo.

#### Segmento 2: Equipo de Desarrollo de Software

1.  Entrevista 1: <br>
    Datos del entrevistado <br>
    Nombre: Fabricio <br>
    Apellidos: Caysedo Salvador<br>
    Edad: 19 <br>
    Distrito: San Martin de Porres <br>

![Foto de entrevista](https://media.discordapp.net/attachments/1048415872450039820/1276770578501730418/Captura_de_pantalla_2024-08-24_000557.png?ex=66cabcc3&is=66c96b43&hm=ee3d0b66f81e99aa57a94ec6397e3803683fd91ba55e81eeedf48e8393dcc0a5&=&format=webp&quality=lossless)

URL: [Link de entrevista](https://drive.google.com/file/d/1uXZ6G0zsHYuDO0gdae2g7U5mKxVTHGnG/view?usp=sharing "Entrevista 1")

Inicio: 0:38<br>
Duracion: 6:52

Resumen:<br>
La entrevista con Fabricio proporcionó información valiosa sobre como un integrante del equipo de desarrollo realiza sus actividades y sus principales desafios. Fabricio nos comenta que la diferencia de pensamientos es un gran problema para un flujo de trabajo continuo y la colaboración. El no ha tenido malas experiencias con otras herramientas gracias a la capacitacion de las mismas. Por otro lado, el considera que la falta de herramientas innovadoras limita el trabajo en equipo, ya que es fundamental conocer un registro de lo avanzado por cada miembro. Así mismo, El cree que las herramientas actualizadas que promueven la gestion y la colaboración deberian ser muy precisas y fiables , pues algunas herramientas tienen fallas. El espera que las herramientas de gestion sean flexibles para adaptarlas a cada modelo de negocio de cada empresa.

2.  Entrevista 2: <br>
    Datos del entrevistado <br>
    Nombre: Agustín<br>
    Apellidos: Aguilar Lindo<br>
    Edad: 21 <br>
    Distrito: San Borja <br>

![Foto de entrevista](https://cdn.discordapp.com/attachments/1257109045723271192/1276971972672225330/image.png?ex=66cb7853&is=66ca26d3&hm=438e8569ec021aeff356b8b71aa8b3528b7cad205b5434810de70968a6c6423f&)

URL: [Link de entrevista](https://drive.google.com/file/d/1GgzFpXSX2uaFr_GiZCo5utxRtd5Z-t24/view?usp=sharing "Entrevista 2")

Inicio: 0:10<br>
Duracion: 6:45

Resumen:<br>
La entrevista a Agustín nos cuenta de primera mano la experiencia como practicante y como las herramientas de gestión actuales influyen. Nos cuenta que su líder de proyecto, para seguir las metodologías Agiles, programa muchas reuniones donde en muchas se redunda en los mismos temas, y el preferiría otra forma de comunicación, problema que podría solucionarse con un programa de gestión. Menciona que una herramienta habitual es GitHub, pero lo considera poco intuitivo y difícil de dominar. Cree firmemente que es necesario una herramienta que ponga más atención en la interfaz de usuario, y a la facilidad de personalizarla.

3.  Entrevista 3: <br>
    Datos del entrevistado <br>
    Nombre: Rodrigo <br>
    Apellidos: Acosa Ramirez<br>
    Edad: 22 <br>
    Distrito: San Miguel <br>

![Foto de entrevista](https://cdn.discordapp.com/attachments/1274759574087270442/1277106218263117896/image.png?ex=66cbf559&is=66caa3d9&hm=cd17ba7cfe17024c2aeb05fbdb32b59deb98bebf9f3fdb1d2a09a4fae44adfa8&)

URL: [Link de entrevista](https://drive.google.com/file/d/1aZ94C1wixcfQNa_dZCZSkIKiBnpPf91i/view?usp=sharing "Entrevista 3")

Inicio: 0:50<br>
Duracion: 10:19

Resumen:<br>
La entrevista con Rodrigo, reveló aspectos clave sobre cómo percibe su entorno de trabajo y los desafíos que enfrenta. Se destacó que herramientas poco intuitivas y sin seguimiente constante pueden ralentizar el trabajo, además que la flexiblidad y adaptabilidad son muy importantes a la hora de acelerar el mismo. Aunque ha logrado adaptarse a las herramientas disponibles, considera que lo detallado con aterioridad limita su eficiencia. Rodrigo espera que en el futuro se desarrollen herramientas que también ofrezcan la flexibilidad necesaria para ajustarse a diferentes entornos y metodologías de trabajo, y que implementen tecnologías emergentes.

### 2.2.3. Análisis de entrevistas

#### Análisis Segmento 1: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento
Durante las entrevistas realizadas a distintos lideres o gerentes de empresas de desarrollo de software indican una necesidad urgente de modernizar las herramientas de gestión de proyectos, con un enfoque en la integración de tecnologías emergentes como la inteligencia artificial. Los entrevistados destacan la importancia de que estas herramientas sean intuitivas, adaptables a diferentes dispositivos y seguras, además de facilitar una integración fluida y una personalización acorde a las necesidades del equipo. También subrayan la importancia de una buena relación costo-beneficio, con un énfasis en que las nuevas soluciones deben mejorar la eficiencia, la colaboración y la protección de datos, al tiempo que se adaptan a las cambiantes demandas del proyecto.

#### Análisis Segmento 2: Equipo de Desarrollo de Software
Las entrevistas revelan que los equipos de desarrollo de software enfrentan desafíos significativos con las herramientas de gestión actuales. Un problema común es la falta de flexibilidad y adaptabilidad de estas herramientas, lo que limita la colaboración y la eficiencia del trabajo en equipo. Las herramientas existentes suelen ser percibidas como poco intuitivas y difíciles de personalizar, lo que afecta tanto la comunicación dentro del equipo como la capacidad para ajustar los procesos a diferentes metodologías de trabajo. Además, se destaca la importancia de contar con herramientas innovadoras que ofrezcan una interfaz de usuario mejorada y un seguimiento constante del progreso. Los entrevistados coinciden en que las herramientas ideales deben ser precisas, fiables y adaptables a los distintos modelos de negocio, con el objetivo de mejorar la gestión de proyectos y optimizar el flujo de trabajo. La incorporación de tecnologías emergentes y la atención a la facilidad de uso son vistas como claves para superar las limitaciones actuales y fomentar una mayor eficiencia y colaboración en los equipos de desarrollo.

### 2.3. Needfinding

### 2.3.1. User Personas

#### Segmento 1: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1257109045723271192/1278469369763991562/Leonardo_Mendoza_1.png?ex=66d0eae2&is=66cf9962&hm=f61347b8dd2034460dbf1c36d06bb5d0adda0458794611bdd6681a77f4e32dbe&">

</p>

#### Segmento 2: Equipo de Desarrollo de Software

<p align="center">

<img src="https://cdn.discordapp.com/attachments/1257109045723271192/1278476848833101954/Oscar_Vargas.png?ex=66d0f1d9&is=66cfa059&hm=9c151f36ea301e19831ef0abb2ae34020ccde2c77c16ef99e8536de820701e8c&">

</p>

### 2.3.2. User Task Matrix

# Comparación de Tareas: Fabricio vs. María

| **Tarea**                                                                    | **FABRICIO Frecuencia** | **FABRICIO Importancia** | **MARÍA Frecuencia** | **MARÍA Importancia** |
| ---------------------------------------------------------------------------- | ----------------------- | ------------------------ | -------------------- | --------------------- |
| Monitorear operaciones y gestionar proyectos                                 | A menudo                | Alta                     | A menudo             | Alta                  |
| Evaluar y seleccionar software de gestión de proyectos                       | A veces                 | Alta                     | A veces              | Alta                  |
| Verificar la adaptabilidad y facilidad de uso del software                   | A veces                 | Alta                     | A veces              | Alta                  |
| Asegurarse de que el software tenga seguridad de datos                       | A veces                 | Alta                     | A veces              | Alta                  |
| Investigar sobre nuevas tecnologías e IA aplicadas a la gestión de proyectos | Mensual                 | Media                    | Mensual              | Media                 |
| Utilizar herramientas de desarrollo para colaboración                        | A menudo                | Alta                     | A menudo             | Alta                  |
| Conducir capacitaciones sobre nuevas herramientas                            | A veces                 | Media                    | A veces              | Media                 |
| Evaluar la precisión y fiabilidad de las herramientas usadas                 | Mensual                 | Alta                     | Mensual              | Alta                  |
| Adaptar herramientas a los modelos de negocio específicos                    | A veces                 | Alta                     | A veces              | Alta                  |
| Mantener un registro del avance de cada miembro del equipo                   | A menudo                | Alta                     | A menudo             | Alta                  |

### 2.3.3. User Journey Mapping 

#### User Journey Mapping - Líder o Gerente de Empresa de Desarrollo de Software

| XXX               | Visualizacion                                                                               | Obtencion                                                                           | Funcionalidad                                                              | Uso                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| User actions      | Identifica problemas en la gestión de proyectos, como la falta de eficiencia o sobrecostos. | Revisa varias opciones y solicita demostraciones.                                   | Coordina la implementación del servicio, asigna roles y responsabilidades. | Monitorea los resultados a través de paneles de control.                 |
| Experience        | Preocupación por el rendimiento de los proyectos y la necesidad de mejorar la rentabilidad. | Toma decisiones basadas en la funcionalidad y costos.                               | Preocupación por el cambio en la cultura                                   | Satisfacción al ver mejoras en la eficiencia y calidad de los proyectos. |
| User expectations | Un servicio que aborde sus problemas específicos de manera eficaz.                          | Una herramienta intuitiva que pueda integrarse fácilmente con los sistemas actuales | Una transición sin problemas, con un soporte técnico eficiente             | Mejoras continuas en la productividad y rentabilidad.                    |

#### User Journey Mapping - Equipo de Desarrollo de Software

| XXX               | Visualizacion                                                      | Obtencion                                                   | Funcionalidad                                                                      | Uso                                                                                                                          |
| ----------------- | ------------------------------------------------------------------ | ----------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| User actions      | Se da cuenta de que los procesos actuales son ineficientes.        | Participa en las demostraciones o pruebas de la herramienta | Completa la capacitación requerida, configura la herramienta según sus necesidades | Utiliza la herramienta diariamente para gestionar tareas, colaborar con el equipo y cumplir con los plazos de los proyectos. |
| Experience        | Interés en cómo una nueva herramienta podría facilitar su trabajo. | Crítica de la herramienta basada en su experiencia          | Curiosidad sobre cómo la nueva herramienta afectará su productividad               | Aprecio por las mejoras en la gestión de proyectos.                                                                          |
| User expectations | Espera una nueva herramienta que simplifique su carga de trabajo . | Nueva herramienta sea fácil de aprender                     | Espera que la curva de aprendizaje sea corta                                       | Espera que el servicio mejore la colaboracion.                                                                               |

### 2.3.4. Empathy Mapping

# Segmento 1: María (Líder/Gerente de Proyecto)

| **¿Qué Piensa y Siente?**                                                                                                | **¿Qué Ve?**                                                                             |
| ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| Necesita garantizar que todos los proyectos se gestionen eficazmente y que el equipo alcance los objetivos establecidos. | Observa un entorno empresarial donde muchas empresas aún usan herramientas anticuadas.   |
| Está interesada en nuevas tecnologías y en cómo pueden mejorar la gestión de proyectos.                                  | Ve que la competencia está adoptando nuevas tecnologías y herramientas más avanzadas.    |
| Quiere un software intuitivo y adaptable que mejore la eficiencia del equipo y proteja los datos de la empresa.          | Nota una creciente integración de la inteligencia artificial en la gestión de proyectos. |
| Lidiar con herramientas obsoletas y encontrar soluciones que se adapten a las necesidades cambiantes de la empresa.      |                                                                                          |

| **¿Qué Dice y Hace?**                                                                                     | **¿Qué Oye?**                                                                                                                   |
| --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Habla sobre la necesidad de modernizar el software y la importancia de la seguridad de los datos.         | Recibe comentarios de su equipo sobre la falta de funcionalidad en las herramientas actuales y las necesidades de capacitación. |
| Busca constantemente nuevas soluciones y herramientas que puedan integrarse y ser útiles para la empresa. | Escucha sobre nuevas tecnologías y herramientas que podrían ser beneficiosas para su empresa.                                   |

| **Dolores**                                                                                                                  | **Ganancias**                                                                                                    |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Experimenta frustraciones con las herramientas obsoletas y la falta de opciones intuitivas que se adapten a sus necesidades. | Una solución moderna y segura que facilite la gestión de proyectos y mejore la colaboración del equipo.          |
| Preocupada por la seguridad de los datos y la posible falta de protección que puedan ofrecer las herramientas actuales.      | La implementación exitosa de un software eficiente que permita al equipo alcanzar sus metas con mayor facilidad. |

# Segmento 2: Fabricio (Equipo de Desarrollo de Software)

| **¿Qué Piensa y Siente?**                                                                                                                 | **¿Qué Ve?**                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Le preocupa que las herramientas actuales limiten la colaboración efectiva y el flujo de trabajo del equipo.                              | Observa que muchas herramientas están desactualizadas y no cumplen con las expectativas actuales del desarrollo de software. |
| Está interesado en herramientas que mejoren la eficiencia y precisión en el desarrollo de software.                                       | Ve que otras empresas están usando herramientas más avanzadas y adaptativas.                                                 |
| Desea trabajar con herramientas innovadoras que faciliten la colaboración y permitan un mejor seguimiento del progreso.                   | Nota una necesidad creciente de herramientas que promuevan una colaboración más efectiva y un registro preciso del trabajo.  |
| Enfrenta desafíos al trabajar con herramientas que no se adaptan bien a las necesidades del equipo y a la falta de capacitación adecuada. |                                                                                                                              |

| **¿Qué Dice y Hace?**                                                                                                   | **¿Qué Oye?**                                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Habla sobre la importancia de la precisión y fiabilidad de las herramientas y cómo estas impactan en su trabajo diario. | Escucha a sus compañeros expresar la necesidad de herramientas más actualizadas y la falta de eficacia de las herramientas actuales. |
| Participa en capacitaciones y busca herramientas que mejoren la colaboración y el seguimiento del progreso del equipo.  | Oye sobre nuevas soluciones y tecnologías que podrían ayudar a resolver problemas de colaboración y precisión.                       |

| **Dolores**                                                                                                                               | **Ganancias**                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Frustraciones:** Frustrado por la falta de herramientas innovadoras que limiten la colaboración y el seguimiento del progreso.          | Herramientas de desarrollo que sean precisas, fiables, y que faciliten una colaboración efectiva.                |
| **Riesgos:** Preocupado por la falta de adaptación de las herramientas a los modelos de negocio y las necesidades específicas del equipo. | Un entorno de trabajo más colaborativo y eficiente con herramientas que se adaptan a las necesidades del equipo. |

### 2.3.5. As-is Scenario Mapping

#### **Segmento 1:** Lider o gerente de empresa de desarrollo de software en crecimiento

| Fases    | Recibir un proyecto                                                                                                                                | Asignar tareas dentro del equipo                                                                                              | Realizar el seguimiento de los miembros                                                                                     | Evaluar el trabajo de los miembros tras culminado el proyecto                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Doing    | - Recibimos un proyecto por parte del área encargada <br> - Realizo una reunión con el equipo para evaluar el proyecto                             | - Asigno tareas especificas a diferentes miembros <br> - Ponemos plazos a los entregables                                     | - Ingreso al repositorio o pregunto a los miembros como van <br> - Anoto los percances y errores que tiene cada miembro     | - Una vez culminado el trabajo, reviso mis apuntes y veo que tal se desenvolvió cada miembro del equipo                                    |
| Thinking | - ¿Será que tenemos las habilidades necesarias para afrontar el proyecto? <br> - ¿Cómo puedo comunicar los objetivos de manera clara?              | - Me toca confiar en las habilidades que algunos miembros dicen tener <br> - Espero que los plazos asignados sean realistas   | - Ojalá estar hacendo un seguimiento eficiente <br> - Espero que los miembros no mientan sobre sus avances                  | - Quiero dar una retroalimentación constructiva basada en hechos reales                                                                    |
| Feeling  | - Presión por dar a entender de manera clara los objetivos y proyecto en general <br> - Confianza en el equipo, pero preocupación por los desafios | - Responsabilidad por asignar las tareas a los miembros correctos <br> - Presión por dejar en claro las tareas a cada miembro | - Frustración cuando los miembros no siguen el ritmo de trabajo <br> - Dudas de si algun miembro mintió acerca de su avance | - Comprometido con el crecimiento del equipo y su mejora continua <br> - Dudas sobre si un miembro comete habitualmente los mismos errores |

#### **Segmento 2:** Miembros de un equipo de Desarrollo de Software

| Fases        | Recibir un proyecto                                                                                                                                | Asignar tareas dentro del equipo                                                                                              | Realizar el seguimiento de los miembros                                                                                     | Evaluar el trabajo de los miembros tras culminado el proyecto                                                                              |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Doing**    | - Recibimos un proyecto por parte del área encargada <br> - Realizo una reunión con el equipo para evaluar el proyecto                             | - Asigno tareas especificas a diferentes miembros <br> - Ponemos plazos a los entregables                                     | - Ingreso al repositorio o pregunto a los miembros como van <br> - Anoto los percances y errores que tiene cada miembro     | - Una vez culminado el trabajo, reviso mis apuntes y veo que tal se desenvolvió cada miembro del equipo                                    |
| **Thinking** | - ¿Será que tenemos las habilidades necesarias para afrontar el proyecto? <br> - ¿Cómo puedo comunicar los objetivos de manera clara?              | - Me toca confiar en las habilidades que algunos miembros dicen tener <br> - Espero que los plazos asignados sean realistas   | - Ojalá estar hacendo un seguimiento eficiente <br> - Espero que los miembros no mientan sobre sus avances                  | - Quiero dar una retroalimentación constructiva basada en hechos reales                                                                    |
| **Feeling**  | - Presión por dar a entender de manera clara los objetivos y proyecto en general <br> - Confianza en el equipo, pero preocupación por los desafios | - Responsabilidad por asignar las tareas a los miembros correctos <br> - Presión por dejar en claro las tareas a cada miembro | - Frustración cuando los miembros no siguen el ritmo de trabajo <br> - Dudas de si algun miembro mintió acerca de su avance | - Comprometido con el crecimiento del equipo y su mejora continua <br> - Dudas sobre si un miembro comete habitualmente los mismos errores |

### 2.4. Ubiquitous Language

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

### **Segmento 1:** Lider o gerente de proyectos de software

| Fases        | Recibir un proyecto                                                                                                                                                                                                        | Asignar tareas dentro del equipo                                                                                                                                                                               | Realizar el seguimiento de los miembros                                                                                                         | Evaluar el trabajo de los miembros tras culminado el proyecto                                                                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Doing**    | - Recibo el proyecto a través de ManageWise con todos los detalles y documentación accesibles <br> - Realizo una reunión virtual en donde se establecen claramente los obetivos y herramientas ofrecidas por la plataforma | - Utilizo ManageWise y esta me sugiere automáticamente la mejor distribución de tareas basada en habilidades y disponibilidad de los miembros <br> - Establezco plazos realistas con la ayuda de la plataforma | - Monitorizo el progreso del equipo a través de dashboards personalizados <br> - Las alertas automáticas me notifican sobre bloqueos y retrasos | - Utilizo la plataforma para analizar el rendimiento de los miembros basado en datos cuantitativos <br> - Ofrezco retroalimentación constructiva con ayuda de los datos proporcionados por ManageWise |
| **Thinking** | - Tengo la seguridad de que el equipo cuenta con todas las herramientas y recursos necesarios                                                                                                                              | - Estoy seguro de que las tareas se han asignado de la mejor manera posible                                                                                                                                    | - Confío en los datos y análisis de la plataforma para realizar un seguimiento efectivo                                                         | - Tengo la confianza de que la evaluación a los miembros es justa                                                                                                                                     |
| **Feeling**  | - Me siento confiado sobre la claridad de los objetivos comunicados y la capacidad del equipo <br> - Motivado porque las herramientas simplifican la planificación                                                         | - Tranquilidad al saber que las tareas están bien distribuidas y los plazos son realistas                                                                                                                      | - Menor estrés gracias a la visibilidad constante del progreso <br> - Seguridad en la gestión efectiva del proyecto                             | Satisfacción al ver mejoras continuas basadas en retroalimentación                                                                                                                                    |

### **Segmento 2:** Miembro de un equipo de desarrollo de software

| Fases        | Recibir las tareas del proyecto                                                                                                        | Colaborar con el equipo                                                                                                                                                            | Desarrollar y probar el código                                                                                                                                  | Entregar el código final y participar en la retrospectiva                                                                                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Doing**    | - Recibo las tareas asignadas directamente en ManageWise, la cual incluye la documentación y requisitos                                | - Me coordino con otros miembros del equipo a través de mensajes desde la plataforma <br> - Accedo a un tablero que muestra el estado del trabajo de todos los miembros del equipo | - Desarrollo y el código y subo una versión preeliminar para ser analizada por el equipo <br> - Accedo a recomendaciones basadas en IA para optimizar el código | - Entrego el código final a través de la plataforma, que también automatiza las revisiones y pruebas finales <br> - Participo en una retroalimentación del equipo basada en datos recopilados durante el proyecto |
| **Thinking** | - Me queda claro lo que se espera de mi y mis tareas                                                                                   | - Estoy bien alineado con el resto del equipo <br> - ¿Hay alguna área donde puedo colaborar más eficientemente?                                                                    | - Aprovecho al máximo las herramientas para mejorar la calidad del código                                                                                       | - Estoy listo para recibir una retroalimentación valiosa <br> - ¿Qué aprendizajes puedo aplicar al próximo proyecto?                                                                                              |
| **Feeling**  | - Confianza en mi comprensión del proyecto y las tareas asignadas <br> - Seguridad en mi capacidad para entregar resultados de calidad | - Motivado por la colaboración fluida                                                                                                                                              | - Satisfacción por el uso de herramientas que mejoran la calidad del trabajo <br> - Tranquilidad al saber que los posibles errores se detectan tempranamente    | - Orgullo del trabajo presentado y entusiasmado por las oportunidades de mejora                                                                                                                                   |

### 3.2. User Stories

EPICS:
|EPIC(ID)|Titulo|Descripcion|
|--------|------|-----------|
|EP01|Optimización de la gestión de tareas|Como líder de proyecto, quiero optimizar la asignación y el seguimiento de tareas para mejorar la eficiencia en el desarrollo y entrega de proyectos.|
|EP02|Colaboración efectiva del equipo|Como líder de equipo, quiero facilitar la colaboración y la comunicación centralizada para mejorar el intercambio de información y coordinación entre los miembros.|
|EP03|Automatización de la gestión del rendimiento|Como líder de proyecto, quiero automatizar el análisis del rendimiento del equipo para identificar oportunidades de mejora de forma eficiente.|
|EP04|Seguridad y control del proyecto|Como administrador de la plataforma, quiero implementar medidas avanzadas de seguridad y control para garantizar la protección de los datos y el éxito del proyecto.|
|EP05|Personalización y adaptabilidad de la plataforma|Como usuario de la plataforma, quiero poder personalizar la interfaz y funciones para adaptar la herramienta a las necesidades específicas del proyecto.|

| User Storiy ID | Título                                          | Descripción |Criterios de Aceptación| Relacionado con(Epic ID) |                                                                                                                                          |
| -------------- | ----------------------------------------------- | ------------|-----------------------|---------------|----------|
|US01| Comentar actividades  |  Como líder del equipo, quiero que la plataforma me permita agregar comentarios a los trabajos y actividades realizadas por los diferentes miembros del equipo, y una vez sean tomados en cuenta, poder eliminarlos.|titulo:<br>Dado que un miembro del equipo está visualizando una tarea, cuando desee agregar un comentario, entonces podrá hacerlo directamente en la sección de comentarios y este se mostrará en tiempo real a todos los miembros del equipo.<br>titulo2:<br>Dado que un comentario ha sido agregado, cuando otros miembros visualicen la tarea, entonces verán el nuevo comentario junto con los anteriores en orden cronológico.|EP02| 
|US02|Análisis de rendimiento basado en IA|Como líder de proyecto, quiero que la plataforma utilice inteligencia artificial para analizar el rendimiento de los miembros del equipo y proporcionar recomendaciones personalizadas para mejorar la eficiencia.|titulo:<br>Dado que el sistema ha recogido datos de rendimiento durante una semana, cuando el líder de proyecto solicite un análisis, entonces el sistema generará un informe detallado utilizando inteligencia artificial, destacando tendencias y áreas de mejora.<br>titulo2:<br>Dado que el análisis de IA está completo, cuando el líder de proyecto lo revise, entonces podrá ver recomendaciones específicas para optimizar el rendimiento del equipo.|EP03|
|US03|Personalización de interfaz|Como usuario de la plataforma, quiero poder personalizar la interfaz según mis preferencias y necesidades para facilitar el acceso rápido a las herramientas y funciones más utilizadas.|titulo:<br>Dado que un usuario desea personalizar su interfaz, cuando acceda a la sección de configuración de la plataforma, entonces podrá seleccionar entre varias opciones de temas y disposiciones para la interfaz.<br>titulo2:<br>Dado que se ha seleccionado un nuevo tema, cuando el usuario guarde los cambios, entonces la interfaz se actualizará de inmediato reflejando la nueva configuración.|EP05|
|US04|Sincronización con herramientas externas|Como líder de proyecto, quiero que la plataforma se integre de manera fluida con otras herramientas y sistemas externos (como calendarios y aplicaciones de mensajería) para centralizar la gestión de proyectos.|titulo:<br>Dado que el equipo usa herramientas externas para la gestión de proyectos, cuando un líder de proyecto configure la sincronización, entonces las tareas y eventos se sincronizarán automáticamente entre la plataforma y las herramientas seleccionadas.<br>titulo2:<br>Dado que la sincronización está activa, cuando se haga un cambio en las herramientas externas o en la plataforma, entonces dicho cambio se reflejará en ambas partes en tiempo real.|EP02|
|US05|Gestión de la seguridad y protección de datos|Como administrador de la plataforma, quiero que el sistema implemente medidas avanzadas de seguridad para proteger los datos sensibles del proyecto y garantizar la privacidad de la información.|titulo:<br>Dado que un usuario intenta acceder a la plataforma, cuando ingrese sus credenciales, entonces el sistema verificará su identidad mediante autenticación de dos factores.<br>titulo2:<br>Dado que se ha realizado un intento de acceso no autorizado, cuando el sistema lo detecte, entonces el administrador recibirá una alerta y el acceso será bloqueado.|EP04|
|US06|Soporte técnico en tiempo real|Como usuario de la plataforma, quiero tener acceso a soporte técnico en tiempo real para resolver problemas rápidamente y mantener la continuidad del trabajo sin interrupciones.|titulo:<br>Dado que un usuario tiene un problema técnico, cuando acceda al soporte técnico en tiempo real, entonces podrá comunicarse con un representante de soporte y recibir asistencia inmediata.<br>titulo2:<br>Dado que el soporte técnico está disponible, cuando el usuario inicie la conversación, entonces recibirá una respuesta dentro de un plazo máximo de 5 minutos.|EP05|
|US07|Informes automatizados de progreso|Como líder de equipo, quiero que la plataforma genere informes automatizados sobre el progreso del proyecto y el desempeño del equipo para tomar decisiones informadas sin tener que crear informes manualmente.|titulo:<br>Dado que un proyecto está en curso, cuando se alcance el final de la semana laboral, entonces el sistema generará automáticamente un informe de progreso que será enviado al líder de proyecto.<br>titulo2:<br>Dado que el informe ha sido generado, cuando el líder de proyecto lo reciba, entonces podrá visualizar el resumen de tareas completadas, en progreso y pendientes.|EP07|
|US08|Herramienta de seguimiento de tareas en tiempo real|Como miembro del equipo, quiero una herramienta que permita el seguimiento de tareas en tiempo real para ver el estado actual y las actualizaciones de los proyectos al instante.|titulo:<br>Dado que un proyecto está activo, cuando un miembro del equipo actualice el estado de una tarea, entonces la herramienta de seguimiento mostrará el cambio en tiempo real a todos los usuarios.<br>titulo2:<br>Dado que un miembro desea ver el progreso general del proyecto, cuando acceda a la herramienta de seguimiento, entonces podrá visualizar un tablero actualizado con el estado actual de todas las tareas.|EP01|
|US09|Adaptación a modelos de negocio|Como gestor de proyectos, quiero que la plataforma pueda adaptarse a diferentes modelos de negocio y metodologías de trabajo para ser flexible y ajustarse a las necesidades específicas de cada proyecto.|titulo:<br>Dado que un líder de proyecto desea configurar la plataforma para adaptarse a un modelo de negocio específico, cuando acceda a la configuración de modelos de negocio, entonces podrá seleccionar y ajustar las plantillas y procesos disponibles.<br>titulo2:<br>Dado que un modelo de negocio ha sido seleccionado, cuando el líder guarde los cambios, entonces la plataforma adaptará automáticamente las funciones y vistas relevantes.|EP01|
|US10|Recordatorios personalizados de plazos y entregas|Como miembro del equipo, quiero recibir recordatorios personalizados sobre los plazos y entregas de las tareas para evitar retrasos y mantener el ritmo adecuado en el proyecto.|titulo:<br>Dado que un usuario ha configurado recordatorios para plazos y entregas, cuando se acerque la fecha límite, entonces el sistema enviará un recordatorio personalizado a través de la plataforma y por correo electrónico.<br>titulo2:<br>Dado que un recordatorio ha sido enviado, cuando el usuario lo reciba, entonces podrá visualizar los detalles de la entrega o tarea pendiente.|EP05|
|US11|Colaboración y comunicación centralizada|Como líder de proyecto, quiero que la plataforma ofrezca herramientas integradas para la colaboración y comunicación centralizada entre los miembros del equipo para mejorar la coordinación y el intercambio de información.|titulo:<br>Dado que un equipo está trabajando en un proyecto, cuando un miembro inicie una conversación o comparta un documento, entonces todos los miembros recibirán una notificación en la plataforma.<br>titulo2:<br>Dado que la comunicación está centralizada, cuando un miembro busque información específica, entonces podrá encontrar todas las conversaciones y documentos relacionados en un solo lugar.|EP02|
|US12|Integración de gráfico radial de habilidades | Como lider de equipo, quiero que la plataforma refleje un gráfico radial sobre las debilidades y fortalezas de cada integrante|titulo:<br>Dado que un proyecto requiere habilidades específicas, cuando el líder de proyecto visualice el gráfico radial de habilidades, entonces podrá ver una representación visual de las competencias de los miembros del equipo.<br>titulo2:<br>Dado que un nuevo miembro se une al equipo, cuando se actualice su perfil con habilidades, entonces el gráfico radial se actualizará automáticamente para reflejar las nuevas capacidades.|EP03|
|US13|Integración de cronogramas| Como lider de equipo, quiero poder sincronizar automáticamente fechas y actividades importantes |titulo:<br>Dado que un proyecto tiene un cronograma establecido, cuando el líder de proyecto lo integre en la plataforma, entonces todas las fechas y hitos importantes serán visibles para el equipo en un calendario compartido.<br>titulo2:<br>Dado que el cronograma está integrado, cuando se realicen cambios en fechas o hitos, entonces estos se reflejarán automáticamente en el calendario compartido.|EP01|
|US14|Alertas ante inactividad o paso de fecha limite | Como lider de equipo, quiero que la plataforma me mande notificaciones cuando algun miembro este inactivo o se haya pasado la fecha límite de entrega |titulo:<br>Dado que una tarea ha estado inactiva durante un período específico, cuando se alcance dicho período, entonces la plataforma enviará una alerta al responsable de la tarea y al líder de proyecto.<br>titulo2:<br>Dado que una tarea ha pasado su fecha límite sin ser completada, cuando se detecte esta condición, entonces la plataforma enviará notificaciones al responsable y al líder de proyecto, destacando la urgencia de la tarea.|EP01|
|US15|Implementación de mensajes directos|Como usuario miembro de un equipo de software, quiero poder enviar mensajes directos al lider y a otros miembros|titulo:<br>Dado que un miembro del equipo necesita comunicarse directamente con otro miembro, cuando envíe un mensaje directo, entonces el destinatario recibirá una notificación instantánea en la plataforma.<br>titulo2:<br>Dado que se ha recibido un mensaje directo, cuando el destinatario lo abra, entonces podrá leer y responder en tiempo real desde la misma interfaz.|EP02|
|US16|Historial de cambios en el proyecto|Como miembro del equipo, quiero poder acceder a un historial detallado de todos los cambios realizados en el proyecto para entender cómo este ha evolucionado y tomar decisiones informadas.|titulo:<br>Dado que se ha realizado un cambio en cualquier aspecto del proyecto, cuando el líder de proyecto revise el historial, entonces podrá ver un registro detallado de todos los cambios, incluyendo quién los realizó y cuándo.<br>titulo2:<br>Dado que el historial de cambios está disponible, cuando un miembro del equipo acceda a él, entonces podrá filtrar los cambios por tipo, fecha y responsable.|EP01|
|US17|Automatización de asignación de tareas|Como líder de proyecto, quiero automatizar la asignación de tareas basadas en las habilidades del equipo para optimizar el flujo de trabajo.|titulo:<br>Dado que existe un proyecto activo, cuando se creen nuevas tareas, entonces el sistema debe asignarlas automáticamente a los miembros más capacitados.|EP01|
|US18|Reportes de tareas atrasadas|Como líder de proyecto, quiero recibir reportes automáticos de tareas atrasadas para tomar medidas correctivas.|titulo:<br>Dado que una tarea está atrasada, cuando se genere el reporte semanal, entonces incluirá un resumen de las tareas pendientes con plazos vencidos.|EP01|
|US19|Gestión de dependencias de tareas|Como miembro del equipo, quiero visualizar las dependencias de tareas para evitar bloqueos y retrasos.|titulo:<br>Dado que una tarea depende de otra, cuando visualice el flujo de tareas, entonces se debe mostrar la relación entre ellas.|EP01|
|US20|Seguimiento de progreso diario|Como líder de proyecto, quiero revisar el progreso diario de las tareas para asegurarme de que se cumplan los plazos.|titulo:<br>Dado que un proyecto está en curso, cuando revise el progreso diario, entonces debo ver el estado actualizado de todas las tareas.|EP01|
|US21|Optimización de asignaciones de recursos|Como gestor de proyectos, quiero que el sistema sugiera la mejor asignación de recursos para proyectos múltiples basándose en la carga de trabajo.|titulo:<br>Dado que el sistema conoce la carga de trabajo, cuando revise la asignación de recursos, entonces el sistema debe proponer asignaciones óptimas.|EP01|
|US22|Espacios de trabajo colaborativos|Como miembro del equipo, quiero tener un espacio colaborativo donde compartir ideas y documentos relacionados con el proyecto.|titulo:<br>Dado que estamos trabajando en equipo, cuando accedamos al espacio colaborativo, entonces podremos compartir y comentar documentos en tiempo real.|EP02|
|US23|Integración con herramientas de videollamadas|Como líder de proyecto, quiero que la plataforma se integre con herramientas de videollamadas para realizar reuniones directamente desde la aplicación.|titulo:<br>Dado que hay una reunión programada, cuando accedamos al evento en la plataforma, entonces podremos iniciar una videollamada integrada.|EP02|
|US24|Foro de discusión del proyecto|Como miembro del equipo, quiero tener acceso a un foro de discusión del proyecto para hacer preguntas y compartir respuestas.|titulo:<br>Dado que tengo una duda, cuando la publique en el foro, entonces los demás miembros del equipo podrán responder.|EP02|
|US25|Historial de conversaciones|Como líder de proyecto, quiero poder acceder al historial de conversaciones para revisar decisiones tomadas durante el desarrollo del proyecto.|titulo:<br>Dado que hubo una conversación relevante, cuando revise el historial, entonces debo poder ver las conversaciones anteriores y sus contextos.|EP02|
|US26|Notificaciones en tiempo real de nuevas actualizaciones|Como miembro del equipo, quiero recibir notificaciones en tiempo real cuando alguien comente o actualice algo importante en el proyecto.|titulo:<br>Dado que una actualización importante ha ocurrido, cuando esté trabajando en la plataforma, entonces recibiré una notificación en tiempo real.|EP02|
|US27|Herramienta de comentarios en documentos compartidos|Como miembro del equipo, quiero hacer comentarios en documentos compartidos para colaborar en la revisión de contenidos.|titulo:<br>Dado que un documento está siendo revisado, cuando haga un comentario, entonces todos los miembros del equipo podrán verlo y responder.|EP02|
|US28|Sistema de evaluación automática de productividad|Como líder de equipo, quiero recibir una evaluación automática semanal de la productividad de cada miembro para identificar fortalezas y áreas de mejora.|titulo:<br>Dado que se ha completado una semana de trabajo, cuando consulte la evaluación, entonces recibiré un análisis detallado del rendimiento individual y colectivo.|EP03|
|US29|Sugerencias de mejoras basadas en IA|Como líder de proyecto, quiero recibir sugerencias automáticas de IA sobre cómo mejorar el rendimiento del equipo basado en los datos recogidos.|titulo:<br>Dado que la IA ha analizado los datos de rendimiento, cuando revise el informe, entonces veré sugerencias específicas de mejoras.|EP03|
|US30|Análisis predictivo de riesgos|Como líder de proyecto, quiero que la plataforma identifique y me notifique automáticamente los posibles riesgos futuros para prevenir problemas.|titulo:<br>Dado que existen datos históricos del proyecto, cuando se produzca un análisis predictivo, entonces se me notificará sobre posibles riesgos.|EP03|
|US31|Reportes automáticos de eficiencia del equipo|Como líder de proyecto, quiero recibir reportes automáticos que muestren la eficiencia general del equipo en términos de tareas completadas y tiempo empleado.|titulo:<br>Dado que el proyecto está en curso, cuando se genere el reporte, entonces incluirá un análisis de la eficiencia del equipo.|EP03|
|US32|Dashboard de métricas clave en tiempo real|Como líder de proyecto, quiero tener acceso a un dashboard con métricas clave en tiempo real para tomar decisiones informadas rápidamente.|titulo:<br>Dado que el proyecto está en desarrollo, cuando acceda al dashboard, entonces veré métricas clave como velocidad de entrega y porcentaje de tareas completadas.|EP03|
|US33|Control de acceso basado en roles|Como administrador, quiero implementar un sistema de control de acceso basado en roles para limitar las funcionalidades a los usuarios autorizados.|titulo:<br>Dado que se ha definido un rol de usuario, cuando acceda a la plataforma, entonces las funcionalidades serán limitadas de acuerdo a su rol.|EP04|
|US34|Copias de seguridad automáticas|Como administrador, quiero que se realicen copias de seguridad automáticas de todos los datos del proyecto para evitar pérdidas.|titulo:<br>Dado que el proyecto está en curso, cuando se complete el día, entonces se generará una copia de seguridad automática.|EP04|
|US35|Monitoreo de actividades sospechosas|Como administrador, quiero ser notificado si la plataforma detecta actividades sospechosas para tomar medidas inmediatas.|titulo:<br>Dado que se detecta actividad sospechosa, cuando revise las notificaciones, entonces seré alertado para tomar acciones correctivas.|EP04|
|US36|Registro de auditoría completo|Como administrador, quiero tener un registro completo de todas las acciones realizadas en la plataforma para realizar auditorías.|titulo:<br>Dado que se realizan cambios en la plataforma, cuando acceda al registro, entonces veré un historial detallado de cada acción.|EP04|
|US37|Autenticación de dos factores (2FA)|Como administrador, quiero implementar autenticación de dos factores para aumentar la seguridad del acceso a la plataforma.|titulo:<br>Dado que un usuario intenta iniciar sesión, cuando se le solicite la 2FA, entonces deberá verificar su identidad con un código adicional.|EP04|
|US38|Temas personalizables para la interfaz|Como usuario de la plataforma, quiero poder elegir entre varios temas para personalizar la interfaz según mis preferencias.|titulo:<br>Dado que quiero personalizar la interfaz, cuando acceda a la configuración de temas, entonces podré elegir entre varias opciones visuales.|EP05|
|US39|Personalización de informes|Como líder de proyecto, quiero personalizar el formato y contenido de los informes generados para adaptarlos a las necesidades específicas del equipo.|titulo:<br>Dado que necesito un informe, cuando acceda a la opción de generación de informes, entonces podré personalizar su formato y contenido.|EP05|
|US40|Integración de widgets personalizados|Como usuario de la plataforma, quiero poder añadir widgets personalizados a mi dashboard para tener acceso rápido a la información más relevante para mí. |titulo:<br>Dado que estoy en el dashboard, cuando acceda a la opción de personalización, entonces podré añadir o eliminar widgets según mis preferencias.|EP05|
|US41|Recordatorios basados en la ubicación|Como usuario de la plataforma, quiero recibir recordatorios personalizados basados en mi ubicación para optimizar el tiempo dedicado a tareas.|titulo:<br>Dado que mi ubicación es relevante para una tarea, cuando esté cerca del lugar necesario, entonces recibiré un recordatorio para completarla.|EP05|
|US42|Configuración avanzada de notificaciones|Como usuario de la plataforma, quiero tener opciones avanzadas para personalizar las notificaciones que recibo, de acuerdo con mi carga de trabajo.|titulo:<br>Dado que quiero ajustar mis notificaciones, cuando acceda a la configuración, entonces podré activar o desactivar notificaciones específicas.|EP05|

### 3.3. Impact Mapping

| Metas                                                                                                                                                                  | Actores                          | Impacto                                           | Entregables                                               |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ------------------------------------------------- | --------------------------------------------------------- |
| x                                                                                                                                                                      | Líder o Gerente de Empresa       | Mejora en la productividad                        | Implementacion de notificaciones y alertas personalizadas |
| x                                                                                                                                                                      |                                  | Aumento en la rentabilidad de la empresa          | Implementacion de automatización de Procesos              |
| Elevar la eficiencia, calidad y rentabilidad de los proyectos en startups de desarrollo de software mediante la optimización de sus procesos de gestión de iniciativas | Equipo de Desarrollo de Software | Mejora de la colaboracion en grupos de trabajo    | Creacion de Tareas transparentes                          |
| x                                                                                                                                                                      |                                  | Reduccion del tiempo de organizacion en proyectos | Implementacion de cronogramas y calendarios integrados    |
| x                                                                                                                                                                      |                                  | Optimizacion del tiempo en tareas diarias         | Integración de documentos de trabajo en tiempo real       |

### 3.4. Product Backlog

| #Orden | User Story ID | Título                                          | Descripción                                                                                                                                           | Story Points <br> (1/2/3/5/8) |
| ------ | ------------- | ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------------------------:|
|1|US01|Comentar actividades|Como líder del equipo, quiero que la plataforma me permita agregar comentarios a los trabajos y actividades realizadas por los diferentes miembros del equipo, y una vez sean tomados en cuenta, poder eliminarlos.|2|
|2|US02|Análisis de rendimiento basado en IA|Como líder de proyecto, quiero que la plataforma utilice inteligencia artificial para analizar el rendimiento de los miembros del equipo y proporcionar recomendaciones personalizadas para mejorar la eficiencia.|8|
|3|US03|Personalización de interfaz|Como usuario de la plataforma, quiero poder personalizar la interfaz según mis preferencias y necesidades para facilitar el acceso rápido a las herramientas y funciones más utilizadas.|3|
|4|US04|Sincronización con herramientas externas|Como líder de proyecto, quiero que la plataforma se integre de manera fluida con otras herramientas y sistemas externos (como calendarios y aplicaciones de mensajería) para centralizar la gestión de proyectos.|5|
|5|US05|Gestión de la seguridad y protección de datos|Como administrador de la plataforma, quiero que el sistema implemente medidas avanzadas de seguridad para proteger los datos sensibles del proyecto y garantizar la privacidad de la información.|5|
|6|US06|Soporte técnico en tiempo real|Como usuario de la plataforma, quiero tener acceso a soporte técnico en tiempo real para resolver problemas rápidamente y mantener la continuidad del trabajo sin interrupciones.|3|
|7|US07|Informes automatizados de progreso|Como líder de equipo, quiero que la plataforma genere informes automatizados sobre el progreso del proyecto y el desempeño del equipo para tomar decisiones informadas sin tener que crear informes manualmente.|3|
|8|US08|Herramienta de seguimiento de tareas en tiempo real|Como miembro del equipo, quiero una herramienta que permita el seguimiento de tareas en tiempo real para ver el estado actual y las actualizaciones de los proyectos al instante.|3|
|9|US09|Adaptación a modelos de negocio|Como gestor de proyectos, quiero que la plataforma pueda adaptarse a diferentes modelos de negocio y metodologías de trabajo para ser flexible y ajustarse a las necesidades específicas de cada proyecto.|5|
|10|US10|Recordatorios personalizados de plazos y entregas|Como miembro del equipo, quiero recibir recordatorios personalizados sobre los plazos y entregas de las tareas para evitar retrasos y mantener el ritmo adecuado en el proyecto.|2|
|11|US11|Colaboración y comunicación centralizada|Como líder de proyecto, quiero que la plataforma ofrezca herramientas integradas para la colaboración y comunicación centralizada entre los miembros del equipo para mejorar la coordinación y el intercambio de información.|5|
|12|US12|Integración de gráfico radial de habilidades | Como lider de equipo, quiero que la plataforma refleje un gráfico radial sobre las debilidades y fortalezas de cada integrante|5|
|13|US13|Integración de cronogramas| Como lider de equipo, quiero poder sincronizar automáticamente fechas y actividades importantes.|5|
|14|US14|Alertas ante inactividad o paso de fecha limite | Como lider de equipo, quiero que la plataforma me mande notificaciones cuando algun miembro este inactivo o se haya pasado la fecha límite de entrega.|3|
|15|US15|Implementación de mensajes directos|Como usuario miembro de un equipo de software, quiero poder enviar mensajes directos al lider y a otros miembros.|3|
|16|US16|Historial de cambios en el proyecto|Como miembro del equipo, quiero poder acceder a un historial detallado de todos los cambios realizados en el proyecto para entender cómo este ha evolucionado y tomar decisiones informadas.|3|
|17|US17|Automatización de asignación de tareas|Como líder de proyecto, quiero automatizar la asignación de tareas basadas en las habilidades del equipo para optimizar el flujo de trabajo.|5|
|18|US18|Reportes de tareas atrasadas|Como líder de proyecto, quiero recibir reportes automáticos de tareas atrasadas para tomar medidas correctivas.|3|
|19|US19|Gestión de dependencias de tareas|Como miembro del equipo, quiero visualizar las dependencias de tareas para evitar bloqueos y retrasos.|3|
|20|US20|Seguimiento de progreso diario|Como líder de proyecto, quiero revisar el progreso diario de las tareas para asegurarme de que se cumplan los plazos.|3|
|21|US21|Optimización de asignaciones de recursos|Como gestor de proyectos, quiero que el sistema sugiera la mejor asignación de recursos para proyectos múltiples basándose en la carga de trabajo.|5|
|22|US22|Espacios de trabajo colaborativos|Como miembro del equipo, quiero tener un espacio colaborativo donde compartir ideas y documentos relacionados con el proyecto.|3|
|23|US23|Integración con herramientas de videollamadas|Como líder de proyecto, quiero que la plataforma se integre con herramientas de videollamadas para realizar reuniones directamente desde la aplicación.|5|
|24|US24|Foro de discusión del proyecto|Como miembro del equipo, quiero tener acceso a un foro de discusión del proyecto para hacer preguntas y compartir respuestas.|2|
|25|US25|Historial de conversaciones|Como líder de proyecto, quiero poder acceder al historial de conversaciones para revisar decisiones tomadas durante el desarrollo del proyecto.|3|
|26|US26|Notificaciones en tiempo real de nuevas actualizaciones|Como miembro del equipo, quiero recibir notificaciones en tiempo real cuando alguien comente o actualice algo importante en el proyecto.|2|
|27|US27|Herramienta de comentarios en documentos compartidos|Como miembro del equipo, quiero hacer comentarios en documentos compartidos para colaborar en la revisión de contenidos.|3|
|28|US28|Sistema de evaluación automática de productividad|Como líder de equipo, quiero recibir una evaluación automática semanal de la productividad de cada miembro para identificar fortalezas y áreas de mejora.|5|
|29|US29|Sugerencias de mejoras basadas en IA|Como líder de proyecto, quiero recibir sugerencias automáticas de IA sobre cómo mejorar el rendimiento del equipo basado en los datos recogidos.|8|
|30|US30|Análisis predictivo de riesgos|Como líder de proyecto, quiero que la plataforma identifique y me notifique automáticamente los posibles riesgos futuros para prevenir problemas.|8|
|31|US31|Reportes automáticos de eficiencia del equipo|Como líder de proyecto, quiero recibir reportes automáticos que muestren la eficiencia general del equipo en términos de tareas completadas y tiempo empleado.|3|
|32|US32|Dashboard de métricas clave en tiempo real|Como líder de proyecto, quiero tener acceso a un dashboard con métricas clave en tiempo real para tomar decisiones informadas rápidamente.|5|
|33|US33|Control de acceso basado en roles|Como administrador, quiero implementar un sistema de control de acceso basado en roles para limitar las funcionalidades a los usuarios autorizados.|5|
|34|US34|Copias de seguridad automáticas|Como administrador, quiero que se realicen copias de seguridad automáticas de todos los datos del proyecto para evitar pérdidas.|3|
|35|US35|Monitoreo de actividades sospechosas|Como administrador, quiero ser notificado si la plataforma detecta actividades sospechosas para tomar medidas inmediatas.|5|
|36|US36|Registro de auditoría completo|Como administrador, quiero tener un registro completo de todas las acciones realizadas en la plataforma para realizar auditorías.|5|
|37|US37|Autenticación de dos factores (2FA)|Como administrador, quiero implementar autenticación de dos factores para aumentar la seguridad del acceso a la plataforma.|5|
|38|US38|Temas personalizables para la interfaz|Como usuario de la plataforma, quiero poder elegir entre varios temas para personalizar la interfaz según mis preferencias.|2|
|39|US39|Personalización de informes|Como líder de proyecto, quiero personalizar el formato y contenido de los informes generados para adaptarlos a las necesidades específicas del equipo.|3|
|40|US40|Integración de widgets personalizados|Como usuario de la plataforma, quiero poder añadir widgets personalizados a mi dashboard para tener acceso rápido a la información más relevante para mí. |3|
|41|US41|Recordatorios basados en la ubicación|Como usuario de la plataforma, quiero recibir recordatorios personalizados basados en mi ubicación para optimizar el tiempo dedicado a tareas.|5|
|42|US42|Configuración avanzada de notificaciones|Como usuario de la plataforma, quiero tener opciones avanzadas para personalizar las notificaciones que recibo, de acuerdo con mi carga de trabajo.|3|