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

| Nombre de <br>los Startups <br> o Empresas |                                                               | Nuestra startup | Competidor 1                                                                                                                                                                                                                                                                                                     | Competidor 2                                                                                                                                                                                       | Competidor 3                                                                                                                                                                                                      |
| ------------------------------------------ | ------------------------------------------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Perfil                                     | Overview                                                      | Horizon         | Wrike                                                                                                                                                                                                                                                                                                            | Trello                                                                                                                                                                                             | ClickUp                                                                                                                                                                                                           |
|                                            | Ventaja competitiva:<br>¿Qué valor ofrece<br> a los clientes? | XXXX            | ofrece análisis predictivos,<br> automatización avanzada y <br>herramientas de colaboración <br>que permiten a los equipos<br> mejorar la productividad y <br>la visibilidad del proyecto<br> en tiempo real.                                                                                                    | Proporciona una interfaz <br>intuitiva y fácil de usar,<br> ideal para equipos pequeños<br> y startups que buscan <br>simplicidad en la gestión <br>de tareas.                                     | Proporciona una solución <br>altamente personalizable <br>que puede adaptarse a <br>diferentes necesidades <br>empresariales, integrando <br>gestión de tareas, tiempo <br>y recursos en una sola <br>plataforma. |
| Perfil de Marketing                        | Mercado Objetivo                                              | XXXX            | Empresas medianas a grandes,<br> así como equipos de proyectos <br>complejos que requieren <br>integración y colaboración <br>avanzadas.                                                                                                                                                                         | Equipos pequeños, startups<br> y empresas que necesitan <br>una herramienta <br>de gestión de proyectos <br>visual y simple.                                                                       | Startups, pequeñas y medianas <br>empresas que buscan una <br>herramienta flexible y completa <br>para la gestión de proyectos.                                                                                   |
|                                            | Estrategias de Marketing                                      | XXXX            | Wrike se posiciona como una <br>herramienta robusta y flexible <br>para equipos que necesitan <br>mejorar la eficiencia operativa <br>y la gestión de proyectos. <br>Su estrategia incluye <br>demostraciones personalizadas <br>y un enfoque en las <br>integraciones con otras <br>herramientas empresariales. | Se enfoca en la simplicidad <br>y la accesibilidad, <br>promocionando su facilidad <br>de uso y la posibilidad de <br>integrarse con herramientas <br>populares como Slack y <br>Google Workspace. | Se posiciona como una alternativa<br> más económica y todo-en-uno a <br>las herramientas tradicionales de <br>gestión de proyectos, con un <br>fuerte enfoque en la personalización<br> y la escalabilidad.       |
| Perfil del producto                        | Productos y servicios                                         | XXXX            | Ofrece un conjunto completo de <br>herramientas de gestión de <br>proyectos, desde la planificación <br>hasta la ejecución, incluyendo <br>paneles de control, cronogramas <br>de Gantt y flujos de trabajo<br> automatizados.                                                                                   | Ofrece tableros Kanban para<br> la gestión de proyectos, con<br> opciones de listas de tareas,<br> etiquetas y archivos adjuntos                                                                   | Ofrece una amplia gama de <br>herramientas para la gestión de <br>tareas, seguimiento del tiempo, <br>automatización de flujos de <br>trabajo y colaboración en equipo.                                           |
|                                            | Precios y Costos                                              | XXXX            | Sus planes varían desde versiones <br>gratuitas limitadas hasta <br>suscripciones empresariales <br>premium, comenzando en<br>aproximadamente $9.80 por<br> usuario/mes.                                                                                                                                         | Ofrece una versión gratuita<br> con limitaciones y planes <br>premium que comienzan en <br>$5 por usuario/mes.                                                                                     | Plan gratuito robusto y planes <br>pagos que comienzan en $5 <br>por usuario/mes.                                                                                                                                 |
|                                            | Canales de distribución <br>(Web y/o Móvil)                   | XXXX            | Se distribuye principalmente a <br>través de su sitio web oficial,<br> con soporte adicional en <br>aplicaciones móviles y a través<br> de integraciones con plataformas<br> como Microsoft Teams y <br>Salesforce.                                                                                              | Distribuido principalmente a <br>través de su sitio web oficial,<br> y también disponible en <br>aplicaciones móviles para iOS <br>y Android.                                                      | Se distribuye a través de su<br> sitio web y tiene aplicaciones<br> para dispositivos móviles,<br> además de extensiones <br>para navegadores.                                                                    |
| Análisis SWOT                              | Fortalezas                                                    | XXXX            | Funcionalidad robusta,<br> integración con otras herramientas<br> empresariales, análisis predictivo.                                                                                                                                                                                                            | Interfaz intuitiva, amplia <br>accesibilidad, integración<br> con múltiples herramientas.                                                                                                          | Altamente personalizable,<br> excelente relación calidad-precio,<br> fuerte integración.                                                                                                                          |
|                                            | Debilidades                                                   | XXXX            | Curva de aprendizaje<br> pronunciada para nuevos usuarios.                                                                                                                                                                                                                                                       | Limitaciones en funciones <br>avanzadas para la gestión<br> de proyectos complejos.                                                                                                                | Puede ser abrumador para <br>usuarios nuevos debido<br> a su vasta cantidad de funciones.                                                                                                                         |
|                                            | Oportunidades                                                 | XXXX            | Expansión en mercados emergentes,<br> desarrollo de nuevas <br> funcionalidades de IA.                                                                                                                                                                                                                           | Expansión de integraciones <br>y nuevas funcionalidades<br> para grandes equipos.                                                                                                                  | Expansión en mercados globales, <br>mejoras continuas en <br>automatización y AI.                                                                                                                                 |
|                                            | Amenazas                                                      | XXXX            | Competencia creciente con <br>herramientas más accesibles <br>y económicas.                                                                                                                                                                                                                                      | Competencia con<br> herramientas que ofrecen <br>más funciones por un costo<br> similar.                                                                                                           | La competencia con<br> herramientas establecidas <br>que tienen una base de<br> usuarios leal.                                                                                                                    |

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

### Segmento: Equipo de Desarrollo de Software

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

Estas preguntas están diseñadas para llevar la conversación de manera lógica y ordenada, desde la comprensión del rol y desafíos actuales hasta la exploración de futuras colaboraciones y expectativas.

### 2.2.2. Registro de entrevistas

#### Segmento 1: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento


#### Segmento 2: Equipo de Desarrollo de Software

 1. Entrevista 1: <br>
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

### 2.2.3. Análisis de entrevistas

#### Análisis Segmento 1: Líder o Gerente de Empresa de Desarrollo de Software en Crecimiento

#### Análisis Segmento 2: Equipo de Desarrollo de Software

### 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

#### **Segmento 1:** Lider o gerente de empresa de desarrollo de software en crecimiento

|Fases | Recibir un proyecto| Asignar tareas dentro del equipo| Realizar el seguimiento de los miembros | Evaluar el trabajo de los miembros tras culminado el proyecto |
|-|-|-|-|-|
| Doing| - Recibimos un proyecto por parte del área encargada <br> - Realizo una reunión con el equipo para evaluar el proyecto| - Asigno tareas especificas a diferentes miembros <br> - Ponemos plazos a los entregables| - Ingreso al repositorio o pregunto a los miembros como van <br> - Anoto los percances y errores que tiene cada miembro| - Una vez culminado el trabajo, reviso mis apuntes y veo que tal se desenvolvió cada miembro del equipo |
| Thinking| - ¿Será que tenemos las habilidades necesarias para afrontar el proyecto? <br> - ¿Cómo puedo comunicar los objetivos de manera clara? | - Me toca confiar en las habilidades que algunos miembros dicen tener <br> - Espero que los plazos asignados sean realistas | - Ojalá estar hacendo un seguimiento eficiente <br> - Espero que los miembros no mientan sobre sus avances |  - Quiero dar una retroalimentación constructiva basada en hechos reales|
| Feeling|- Presión por dar a entender de manera clara los objetivos y proyecto en general <br> - Confianza en el equipo, pero preocupación por los desafios| - Responsabilidad por asignar las tareas a los miembros correctos <br> - Presión por dejar en claro las tareas a cada miembro| - Frustración cuando los miembros no siguen el ritmo de trabajo <br> - Dudas de si algun miembro mintió acerca de su avance|- Comprometido con el crecimiento del equipo y su mejora continua <br> - Dudas sobre si un miembro comete habitualmente los mismos errores|

#### **Segmento 2:** Miembros de un equipo de Desarrollo de Software 

|Fases | Recibir un proyecto| Asignar tareas dentro del equipo| Realizar el seguimiento de los miembros | Evaluar el trabajo de los miembros tras culminado el proyecto |
|-|-|-|-|-|
| **Doing**| - Recibimos un proyecto por parte del área encargada <br> - Realizo una reunión con el equipo para evaluar el proyecto| - Asigno tareas especificas a diferentes miembros <br> - Ponemos plazos a los entregables| - Ingreso al repositorio o pregunto a los miembros como van <br> - Anoto los percances y errores que tiene cada miembro| - Una vez culminado el trabajo, reviso mis apuntes y veo que tal se desenvolvió cada miembro del equipo |
| **Thinking**| - ¿Será que tenemos las habilidades necesarias para afrontar el proyecto? <br> - ¿Cómo puedo comunicar los objetivos de manera clara? | - Me toca confiar en las habilidades que algunos miembros dicen tener <br> - Espero que los plazos asignados sean realistas | - Ojalá estar hacendo un seguimiento eficiente <br> - Espero que los miembros no mientan sobre sus avances |  - Quiero dar una retroalimentación constructiva basada en hechos reales|
| **Feeling**|- Presión por dar a entender de manera clara los objetivos y proyecto en general <br> - Confianza en el equipo, pero preocupación por los desafios| - Responsabilidad por asignar las tareas a los miembros correctos <br> - Presión por dejar en claro las tareas a cada miembro| - Frustración cuando los miembros no siguen el ritmo de trabajo <br> - Dudas de si algun miembro mintió acerca de su avance|- Comprometido con el crecimiento del equipo y su mejora continua <br> - Dudas sobre si un miembro comete habitualmente los mismos errores|

### 2.4. Ubiquitous Language

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

### **Segmento 1:** Lider o gerente de proyectos de software 

| Fases | Recibir un proyecto | Asignar tareas dentro del equipo | Realizar el seguimiento de los miembros | Evaluar el trabajo de los miembros tras culminado el proyecto |
|-|-|-|-|-|
| **Doing** | - Recibo el proyecto a través de ManageWise con todos los detalles y documentación accesibles <br> - Realizo una reunión virtual en donde se establecen claramente los obetivos y herramientas ofrecidas por la plataforma | - Utilizo ManageWise y esta me sugiere automáticamente la mejor distribución de tareas basada en habilidades y disponibilidad de los miembros <br> - Establezco plazos realistas con la ayuda de la plataforma | - Monitorizo el progreso del equipo  a través de dashboards personalizados <br> - Las alertas automáticas me notifican sobre bloqueos y retrasos | - Utilizo la plataforma para analizar el rendimiento de los miembros basado en datos cuantitativos <br> - Ofrezco retroalimentación constructiva con ayuda de los datos proporcionados por ManageWise |
| **Thinking** | - Tengo la seguridad de que el equipo cuenta con todas las herramientas y recursos necesarios| - Estoy seguro de que las tareas se han asignado de la mejor manera posible | - Confío en los datos y análisis de la plataforma para realizar un seguimiento efectivo | - Tengo la confianza de que la evaluación a los miembros es justa |
| **Feeling** | - Me siento confiado sobre la claridad de los objetivos comunicados y la capacidad del equipo <br> - Motivado porque las herramientas simplifican la planificación | - Tranquilidad al saber que las tareas están bien distribuidas y los plazos son realistas | - Menor estrés gracias a la visibilidad constante del progreso <br> - Seguridad en la gestión efectiva del proyecto | Satisfacción al ver mejoras continuas basadas en retroalimentación |


### **Segmento 2:** Miembro de un equipo de desarrollo de software 

| Fases | Recibir las tareas del proyecto | Colaborar con el equipo | Desarrollar y probar el código | Entregar el código final y participar en la retrospectiva |
|-|-|-|-|-|
| **Doing** | - Recibo las tareas asignadas directamente en ManageWise, la cual incluye la documentación y requisitos | - Me coordino con otros miembros del equipo a través de mensajes desde la plataforma <br> - Accedo a un tablero que muestra el estado del trabajo de todos los miembros del equipo | - Desarrollo y el código y subo una versión preeliminar para ser analizada por el equipo <br> - Accedo a recomendaciones basadas en IA para optimizar el código | - Entrego el código final a través de la plataforma, que también automatiza las revisiones y pruebas finales <br> - Participo en una retroalimentación del equipo basada en datos recopilados durante el proyecto |
| **Thinking** | - Me queda claro lo que se espera de mi y mis tareas | - Estoy bien alineado con el resto del equipo <br> - ¿Hay alguna área donde puedo colaborar más eficientemente? | - Aprovecho al máximo las herramientas para mejorar la calidad del código | - Estoy listo para recibir una retroalimentación valiosa <br> - ¿Qué aprendizajes puedo aplicar al próximo proyecto? |
| **Feeling** | - Confianza en mi comprensión del proyecto y las tareas asignadas <br> - Seguridad en mi capacidad para entregar resultados de calidad | - Motivado por la colaboración fluida | - Satisfacción por el uso de herramientas que mejoran la calidad del trabajo <br> - Tranquilidad al saber que los posibles errores se detectan tempranamente | - Orgullo del trabajo presentado y entusiasmado por las oportunidades de mejora | 

### 3.2. User Stories

### 3.3. Impact Mapping

### 3.4. Product Backlog
