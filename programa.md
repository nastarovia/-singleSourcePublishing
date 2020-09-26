(descargar el programa del curso en [PDF](https://drive.google.com/file/d/13BvWvpSgpXSc1BysDr9cMMavre0hEmaY/view?usp=sharing))


"Introducción al *Single source publishing*" es un taller donde desarrollaremos las competencias básicas necesarias para desarrollar flujos de trabajo sostenibles de publicación digital multiformato a partir de un único conjunto de archivos. Estudiaremos los conceptos básicos de la publicación digital, como son la separación del contenido y su presentación y la importancia de trabajar con contenido estructurado semánticamente en lenguajes de marcado. Aprenderemos a trabajar con la línea de comandos y a configurar y desarrollar contenido utilizando editores de texto (no es lo mismo que un _procesador de texto_, como MS Word o Libre Office). Exploraremos herramientas avanzadas de conversión de formatos y manipulación de texto (Pandoc) y control de versiones (Git). Aprenderemos a crear y administrar proyectos colaborativos y publicar documentación en la web con GitHub. Y por último, exploraremos cómo integrar y personalizar estas herramientas dentro de flujos de trabajo automatizados, para ganar en eficiencia y competitividad. Este curso ha sido diseñado para adaptar herramientas avanzadas en edición y publicación digital a las necesidades de editores en general. Puede considerarse como una introducción general a la programación diseñada específicamente para editores.

## Por qué tomar este curso

Si como editor (o administrador de cualquier tipo de documentación) has tenido alguna vez problemas con [https://lavoragine.GitHub.io/tutorial/] este taller te entregará herramientas para desarrollar soluciones personalizadas a estos problemas.

## Objetivos del curso

### General
- Proporcionar una introducción general al _single source publishing_ (también conocido como *multichanel publishing*), esto es: los flujos de trabajo en edición que parten de un único archivo (o set de archivos) para obtener múltiples formatos de salida. Al final del curso, los participantes serán capaces de crear sus propios flujos de trabajo automatizados para obtener un libro en formato PDF para impresión, un libro electrónico (en formato EPUB o mobi), y una página web alojada en GitHub, con máxima eficiencia y sostenibilidad. De esta manera, los participantes del workshop obtendrán una comprensión general de las  herramientas utilizadas y serán capaces de adaptarlas a sus propias necesidades.

### Específicos
- Introducir el concepto de la estructuración semántica del texto a través del uso de lenguajes de marcado. O lo que es equivalente: trabajar el concepto básico de la edición digital: la separación entre contenido y su presentación.
- Aprender cómo formatear archivos y utilizar diferentes programas (software) para automatizar tareas
- Aprender a configurar y gestionar un sistema fiable y colaborativo de control de versiones, utilizando plataformas de alto nivel
- Familiarizarse con técnicas avanzadas de automatización de procesos editoriales
- Familiarizarse con técnicas de publicación libre de documentación de proyectos
- Aprender a crear metadata relevante y a diseminarla a través de los sistemas de intercambio de información estandares
- Comprender los estandares de accesibilidad y cómo producir libros que sean nacidos accesibles
- Adquirir el _background_ tecnológico necesario para explorar otras herramientas en el vasto ecosistema de desarrollos de software libre e investigar sobre sus posibles implementaciones, lo cual supone, en último termino, obtener la capacidad de innovar a partir de sus realidades específicas.

## Bibliografía básica

- Al principio fue la línea de comandos, Neil Stephenson (está disponible online en: <https://www.traficantes.net/sites/default/files/pdfs/En%20el%20principio%20fue...-TdS.pdf>), traducido por Asunción Álvarez (2003)
- Dennis Tenen y Grant Wythoff, "Escritura sostenible en texto plano usando Pandoc y Markdown", traducido por Víctor Gayol, The Programming Historian en español 1 (2017), https://doi.org/10.46430/phes0008.

## Web del curso:

La web del curso, donde estará disponible la documentación general y los tutoriales en video. Se construirá en Jekyll y se hospedará en GitHub Pages utilizando una plantilla personalizada, originalmente creada por P2PU. Un demo se puede ver en:
<https://nastarovia.github.io/course-in-a-box/>

## Software para instalar ANTES de comenzar el curso

(se preverá de instrucciones detalladas de instalación para cada programa y según sistema operativo)

- Atom + extensiones
- Pandoc
- Ruby
- Jekyll
- Sigil
- Git
- GitHub Desktop

Se asume que todos los participantes tienen inDesign instalado en su sistema y un conocimiento suficientemente de su uso.


## Programa del taller

El taller está dividido en 8 módulos. La documentación correspondiente a cada uno de los módulos estará disponible en la página web del taller, alojada en GitHub, y constará de una presentación en texto, videotutoriales (sobre todo para explicar temas de configuración de software o uso de herramientas), y Hojas de resumen (descargables) de comandos. Se pedirá que cada participante al taller proponga un proyecto (un libro o una colección de libros) que ira desarrollando a lo largo de los módulos. Cada modulo será complementado por un chat abierto para aclarar conceptos, ampliar información, resolver dudas, y dar orientación sobre los proyectos que cada participante lleva a cabo durante el taller.

### Primer módulo:   _Single source publishing_. Lenguajes de marcado y contenido estructurado

- Un libro es estructura, contenido, y presentación
- Que es un lenguaje de marcado (o etiquetado)
- fundamentos de HTML y CSS
- Editor de texto vs procesador de texto
- Introducción a Markdown

### Segundo módulo: Línea de comandos e interacción avanzada con un computador

- La línea de comandos
- Manipular archivos con el terminal
- Repositorios y arboles de archivos
- Utilizar programas desde la línea de comandos

### Tercer módulo: Convertir y manipular formatos de texto

- Convertir formatos de texto con Pandoc
- Yaml  Metadata Blocks: manipular metadata en Pandoc
- Modificar plantillas
- Trabajar con filtros y procesadores

### Cuarto módulo: Automatización y construcción de flujos de trabajo

- Crear nuestro flujo de trabajo
- Mapear estilos (de Markdown a InDesign)
- EPUB, HTML y Accesibilidad (Metadata y WAI-ARIA roles)
- Kindlegen y Amazon Kindle

### Quinto módulo: Control de versiones con GIT

- Git: fundamentos del control de versiones
- Registrar y administrar cambios
- Crear y fusionar versiones de un proyecto


### Sexto módulo : Colaborar en red con GitHub

- GitHub, una plataforma colaborativa y abierta
- Sincronizar un repositorio local con un repositorio remoto
- Colaborar: *Fork* y *Pull request*
- Administrar proyectos: GitHub Issues y GitHub Projects

### Septimo módulo: Llevar nuestro *workflow* a la nube
- Conectar todo: llevar nuestro flujo de trabajo a la nube
- *Make* file: de MarkDown a PDF en un clic
- Publicar con licencias libres. Qué son y para que sirven.
- Administrar correcciones y lanzamientos
- Publicar formatos de libro (PDF, EPUB, mobi)
- Publicar formatos web (GitHub Wiki, GitHub Pages)

### Octavo módulo:
- Presentación de proyectos y discusión
- Conclusiones
