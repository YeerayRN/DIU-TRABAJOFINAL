# Trabajo Final DIU: Portfolio UX y Caso de Estudio GREEN BITES

**Autor:** Yeray  
**Fecha:** Junio 2026  

---

## PARTE I: MI EXPERIENCIA UX

Cuando entré a la carrera, la verdad es que pensaba que hacer software era básicamente picar código como un loco, pelearme con el backend, ajustar las bases de datos y rezar para que la aplicación no petara en la presentación. El tema del diseño me daba un poco igual; pensaba que con poner cuatro botones que funcionasen y un fondo que no hiciese daño a los ojos, ya estaba todo hecho. Del mismo modo que cuando configuro mi teclado mecánico, optimizo los perfiles de iluminación RGB o ajusto las velocidades PCIe en mi PC busco que la máquina rinda al máximo sin cuellos de botella, he tenido que asistir a esta asignatura para darme cuenta de que el usuario busca exactamente lo mismo al entrar a una web: cero fricción. Puedes montarte la mejor arquitectura del mundo y tener un rendimiento perfecto, pero si la persona que coge el móvil o el ratón no entiende nada y se frustra a los diez segundos, todo tu trabajo no sirve absolutamente para nada. En este documento voy a contar un poco todo lo que he aprendido y cómo he pasado de hacer interfaces a lo loco a pensar de verdad en la persona que hay al otro lado de la pantalla.

### 1.1. Aportaciones y contribuciones en ejercicios de clase
En las clases teóricas y en las prácticas de análisis, mi principal cambio de enfoque fue dejar de lado las valoraciones subjetivas (como decir simplemente que un diseño me parecía "feo" o "complejo") para usar criterios objetivos. Aprendí a auditar interfaces aplicando las 10 Heurísticas de Usabilidad de Nielsen, lo cual me dio un marco de trabajo real para argumentar mis decisiones.

Por ejemplo, al evaluar portales web reales, me centré en identificar fallos en la Visibilidad del estado del sistema, penalizando las páginas que no daban feedback al usuario tras hacer clic en un botón, lo que genera frustración. También busqué problemas de Consistencia y estándares, notando cómo cambiar de sitio elementos comunes (como el menú de navegación) obliga al usuario a aprender a usar la web desde cero. Es algo que todos sufrimos a diario; por ejemplo, al intentar lidiar con plataformas burocráticas para buscar el Anexo I o subir documentación para solicitar la Beca Santander Estudios, te das cuenta de lo desesperante que resulta una interfaz que no te lleva de la mano ni te confirma si el proceso se ha guardado correctamente.

Además, apliqué activamente las Leyes de la Gestalt. Entendí que agrupar elementos visuales (Ley de Proximidad) o mantener un estilo uniforme en los botones interactivos (Ley de Similitud) no es una cuestión de pura estética, sino una estrategia directa para reducir la carga cognitiva del usuario y hacer que la interfaz sea más fácil de procesar mentalmente.

Las actividades realizadas en clase me han parecido una manera entretenida e interactiva a la vez que útil de asentar de manera práctica los conceptos enseñados por el profesor. Estuvo muy bien discutir con los compañeros de mi grupo, como Jose, sobre qué aspectos podían mejorarse de una página, hacer las pruebas de eye tracking y debatir sobre por qué ciertas decisiones de diseño que parecían buenas en papel, en la práctica eran un desastre.
Las actividades realizadas en clase me han parecido una manera entretenida e interactiva a la vez que útil de asentar de manera práctica los conceptos enseñados por el profesor. Estuvo muy bien discutir con los compañeros de mi grupo sobre qué aspectos podían mejrorarse de una página, hacer el eye tracking, etc.

### 1.2. Aportaciones destacables en las Prácticas (Caso: The Champions Burger)
El proyecto donde más he aplicado y consolidado estos conocimientos ha sido el diseño de la plataforma interactiva para el festival The Champions Burger. Nuestro objetivo era solucionar problemas reales de este tipo de eventos, como la saturación incontrolable en las colas físicas y la falta de información clara sobre ingredientes.

Investigación y Empatía (UX Research)
Mi primera aportación clave fue frenar el impulso de empezar a diseñar directamente en Figma. Dedicamos un tiempo valiosísimo a crear User Personas y Journey Maps para empatizar de verdad con los asistentes del festival. Esto nos permitió identificar puntos de dolor reales, como la frustración de no saber el tiempo de espera en un food truck o la enorme dificultad y ansiedad de los usuarios celíacos para encontrar opciones seguras sin tener que preguntar puesto por puesto. Construir el modelo mental de estos usuarios antes de tirar la primera línea nos dio un mapa de ruta clarísimo.

Arquitectura de la Información y Prototipado
Para la construcción del prototipo, implementamos la metodología de Atomic Design. Esta forma de trabajar nos permitió crear un sistema de componentes modular y escalable (empezando por átomos como la tipografía y los colores, pasando por moléculas como las tarjetas de las hamburguesas, hasta llegar a organismos como el sistema de filtrado). Esto mantuvo una consistencia visual perfecta en toda la aplicación. Además, apliqué la Ley de Hick para no sobrecargar los menús. Sabiendo que el tiempo de decisión de un usuario aumenta exponencialmente con el número de opciones, estructuramos la navegación asegurando que tareas vitales (como filtrar productos sin gluten o localizar un puesto en el mapa) estuvieran siempre a un par de clics, agilizando la experiencia.

Evaluación, Métricas y Testing (UX Testing)
Esta fue la fase más reveladora para mí. Acordamos no conformarnos con nuestra propia opinión sesgada sobre el prototipo y realizamos un estudio empírico de A/B Testing contra el diseño de otro grupo (Diseño B). Utilicé GazeMapping para generar mapas de calor (Eye Tracking). Los resultados demostraron que, en nuestro diseño, la mirada de los usuarios iba directamente a los Puntos de Interés (POI) como los botones de reserva y el filtro de alérgenos. Mientras tanto, en el Diseño B el escaneo visual era totalmente errático, formando un patrón de búsqueda caótico por la falta de una jerarquía visual lógica.

Además, me encargué de administrar y analizar el cuestionario SUS (System Usability Scale) con Tally. Fue muy interesante entender la matemática detrás de este estándar de la industria, donde las preguntas pares e impares se puntúan de forma inversa para evitar que el usuario conteste en piloto automático. Nuestro diseño alcanzó una puntuación de 91.5/100 (Grado A, rozando la excelencia), frente al 60/100 del otro diseño. Estos datos validaron objetivamente la superioridad de nuestra propuesta.

### 1.3. Utilidad de la asignatura en otros proyectos
Quizá el mayor éxito de esta asignatura es que me ha dotado de un conjunto de herramientas mentales que ahora aplico inconscientemente en otras ramas de la carrera y en mis proyectos personales.

SIBW (El Pollo Motrileño)

Un ejemplo clarísimo de esto ocurrió recientemente, cuando estuve inmerso en un proyecto de desarrollo web para la asignatura de SIBW, donde tuvimos que crear El Pollo Motrileño, un portal web de noticias local. Antes de cursar DIU, me habría limitado a volcar el contenido HTML y CSS sin más, asegurándome únicamente de que las etiquetas cerraran bien.

Sin embargo, esta vez me paré a estructurar la información siguiendo los principios de interfaz gráfica. Apliqué el concepto de espacios en blanco (white space) para dar respiro visual a la lectura de las noticias, entendiendo que el espacio vacío es un elemento de diseño tan importante como el texto mismo. Cuidé minuciosamente la legibilidad de las tipografías, el contraste del logotipo y trabajé a fondo la adaptación a dispositivos móviles. Me aseguré de que el tamaño de las fuentes fuera el adecuado y de que todos los enlaces a las noticias tuvieran un área táctil (touch target) lo bastante grande para que cualquier persona pudiera navegar desde su smartphone sin pulsar la noticia equivocada por error. Si todo llama la atención en una web, al final nada llama la atención, y eso es algo que tuve muy presente al definir la cabecera y el pie de página de este portal.

### 1.4. Autoevaluación de Experiencia UI/UX
Mirando en retrospectiva mi evolución a lo largo de este cuatrimestre, considero que mi avance ha sido muy sólido. He logrado dejar atrás de una vez por todas la mentalidad tóxica de que "si el código funciona y hace lo que se le pide, es culpa del usuario si es demasiado torpe para entenderlo". Ahora asumo la responsabilidad completa de la experiencia de navegación. Si un usuario se pierde en una aplicación que yo he desarrollado, el fallo no está en su capacidad de comprensión, sino en mi capacidad para guiarlo a través de la interfaz.

He aprendido a tomar decisiones de diseño y arquitectura de software respaldándome estrictamente en datos objetivos (métricas estandarizadas como el cuestionario SUS, análisis biométricos de Eye Tracking y auditorías técnicas) en lugar de guiarme por simples preferencias estéticas personales o modas pasajeras.

Gracias a esta asignatura, me siento verdaderamente capacitado para enfrentarme a interfaces en el mundo real, auditar proyectos existentes para detectar deficiencias de usabilidad, y plantear rediseños completos. Sé cómo construir productos digitales que no solo sean viables y robustos a nivel de código frontend, sino que ofrezcan una experiencia fluida, universal, intuitiva y, por encima de todo, cien por cien satisfactoria para la persona que, al final del día, está al otro lado de la pantalla intentando resolver un problema.

---

## PARTE II: CASO DE ESTUDIO - PROPUESTA DE DISEÑO ECO MERCADO UGR

### 2.1. Análisis de Iniciativas Reales de Mercados Ecológicos
Para fundamentar el diseño del ECOMERCADO UGR, se ha realizado un análisis heurístico y de usabilidad de plataformas existentes en el sector, evaluando su diseño bajo criterios objetivos.

#### Análisis de Huerta Madrid
*   **Usabilidad y Arquitectura de la Información:**
Visibilidad y Arquitectura:
Desde el primer momento al entrar en la página, queda claro que estamos tratando con la web de una empresa de agricultores que venden productos directamente de sus huertas. La página presenta un header con su logo y una barra de navegación que permite acceder a las distintas
secciones de la página de manera ágil. Gracias a esta barra, el usuario puede acceder a la tienda y comenzar a seleccionar los productos que desee en un solo clic, lo cual es excelente. Sin embargo, al profundizar en la sección de la tienda, la arquitectura de la información empieza a presentar fricciones. El catálogo carece de un sistema de filtrado avanzado eficiente (por ejemplo, poder separar rápidamente verduras, frutas de temporada o cestas preconfiguradas). Al mostrar todos los productos en listas extensas, se corre el riesgo de incumplir la Ley de Hick, aumentando innecesariamente la carga cognitiva del usuario, que se ve obligado a hacer un scroll prolongado y a leer ítem por ítem para encontrar lo que busca.

Consistencia y Estándares:
Analizando las heurísticas de Nielsen, la interfaz presenta deficiencias en la Visibilidad del estado del sistema. Faltan microinteracciones claras; por ejemplo, al pasar el cursor sobre los productos o los botones de compra, el feedback visual (como un cambio de color o una elevación de la tarjeta mediante CSS) es escaso o inexistente. Esto genera dudas sobre si un elemento es realmente clicable o no. Además, a nivel de consistencia, sería ideal que el diseño contara con breadcrumbs en las fichas de producto, para que el usuario siempre sepa en qué nivel de la tienda se encuentra y pueda retroceder sin depender exclusivamente del botón "Atrás" del navegador.


*   **Adaptación a dispositivos (Responsive):**
Teniendo en cuenta que el usuario típico consultará esta web desde su smartphone mientras organiza su compra semanal, la vista móvil presenta áreas de mejora. Al apilarse los elementos, algunos Touch Targets (áreas táctiles de los botones y enlaces) quedan demasiado juntos. Esto penaliza la ergonomía y aumenta la probabilidad de que el usuario pulse un producto o enlace equivocado por error. En la vista móvil, el contenido debería repriorizarse para evitar un desplazamiento vertical excesivo.

*   **Accesibilidad:
*   Para evaluar el nivel de inclusión del portal, he realizado una auditoría técnica tomando como referencia las pautas de accesibilidad WCAG 2.1 y utilizando herramientas automatizadas como Google Lighthouse y WAVE. Los resultados muestran varias barreras críticas que impiden una experiencia universal:

Problemas de Contraste (WCAG 1.4.3 - Contraste mínimo): Como suele ser habitual en plataformas de temática ecológica, se abusa de la paleta de colores verdes. He detectado textos descriptivos (como precios o detalles del envío) en verde claro o gris sobre fondos blancos, así como texto blanco superpuesto directamente a imágenes del huerto sin un filtro de oscurecimiento. Estos elementos no alcanzan el ratio mínimo de contraste (4.5:1), dificultando la lectura a personas con problemas de visión o a usuarios que navegan desde el móvil a plena luz del sol.

Imágenes sin texto alternativo (WCAG 1.1.1 - Contenido no textual): Una parte importante del catálogo visual (fotografías de las verduras, cestas y agricultores) carece del atributo alt en el HTML. Los usuarios que dependen de lectores de pantalla no reciben ninguna descripción de estos elementos, perdiéndose el contexto humano y la confianza que la web intenta transmitir.

Navegación por teclado y Foco (WCAG 2.1.1 y 2.4.7): Al intentar recorrer el catálogo y añadir productos al carrito utilizando exclusivamente la tecla Tab, resulta imposible operar la web con normalidad. La ausencia de una propiedad CSS :focus visible impide saber en qué elemento de la pantalla se encuentra el usuario, bloqueando por completo la compra a personas con limitaciones motoras que no pueden usar el ratón.

Estructura Semántica de Encabezados: La herramienta WAVE revela saltos estructurales (por ejemplo, pasando de un <H1> directamente a un <H3>). Aunque parece un detalle menor a nivel visual, destruye la arquitectura lógica de la página para las tecnologías de asistencia, que utilizan estos encabezados para crear un índice de navegación del sitio.


### 2.2. Insights y Propuesta de Valor para ECOMERCADO UGR

Basado en el análisis previo y en la información del proyecto Ecomercado UGR, planteo las siguientes hipótesis de diseño:

*   **¿Quién es el usuario? (User Persona):** Principalmente, comunidad universitaria (estudiantes, PDI, PAS) preocupados por la sostenibilidad, el comercio justo y los productos locales de temporada.
*   **¿Qué buscan/necesitan? (User Needs):** Información clara sobre fechas y localizaciones (ej. edición del 28 de mayo), transparencia sobre el origen de los productos, y facilidad para contactar o reservar a los productores locales.
*   **Puntos Fuertes del Factor Humano a potenciar:** La confianza y el sentimiento de comunidad (Economía Circular). El diseño debe transmitir cercanía, usando imágenes reales de los agricultores y tipografías legibles y amables.

**Propuesta de Valor:**
Crear una plataforma digital (formato App/Web PWA) que funcione no solo como directorio de productores, sino como un canal de fidelización para la comunidad universitaria, permitiendo consultar el calendario de los ecomercados y pre-reservar cestas de temporada.

### 2.3. Propuesta de Diseño (Boceto / Mockup)

*(Añade aquí la imagen de tu boceto (basta con un wireframe de baja/media fidelidad hecho en Figma o incluso en papel escaneado) de cómo sería la Home o la pantalla principal de Ecomercado UGR).*

`![Boceto de la App Ecomercado UGR](enlace_a_tu_imagen)`

**Justificación del diseño:**
*   [Explica por qué has puesto los elementos donde están. Ej: "Se ha colocado un CTA primario visible para consultar la próxima fecha, reduciendo la carga cognitiva..."].

### 2.4. Conclusión: Relación con las Prácticas de DIU (Autoevaluación)

Si tuviera que aplicar lo aprendido en las prácticas (Caso *The Champions Burger*) a este nuevo proyecto real del ECOMERCADO UGR:

*   **Lo que replicaría:** Aplicaría desde el minuto cero la metodología de **A/B Testing** y las auditorías de accesibilidad con **Lighthouse/WAVE**. Además, usaría **Tally** para crear un cuestionario SUS rápido tras las primeras interacciones con los usuarios de la UGR para iterar rápido.
*   **Lo que me ha faltado en prácticas y aplicaría aquí:** [Ej: En las prácticas el enfoque fue muy cerrado a un prototipo específico. En este caso real, sería vital hacer un estudio de campo real (investigación etnográfica) acudiendo físicamente a un Eco Mercado para entrevistar a los agricultores y entender sus limitaciones tecnológicas antes de diseñarles un sistema de reservas].

---

## 3. Bibliografía y Herramientas
*   Nielsen, J. (1994). *10 Usability Heuristics for User Interface Design*. Nielsen Norman Group.
*   W3C. *Web Content Accessibility Guidelines (WCAG)*.
*   Herramientas utilizadas en el análisis: Google Lighthouse, WAVE Accessibility Tool, Figma.
