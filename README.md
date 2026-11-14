#Una galaxia ✨🌌

Una experiencia web interactiva, romántica y con temática espacial diseñada para hacer una declaración especial. Este proyecto utiliza animaciones en Canvas y manipulación del DOM para crear un recorrido visual hasta llegar a "La pregunta".

🚀 Características Principales

Fondo Animado (Canvas): Una galaxia generada por código que gira lentamente, con estrellas de fondo y diferentes tonalidades de colores. La velocidad cambia dependiendo de la sección en la que se encuentre el usuario.

Narrativa por Fases: El contenido está dividido en "pasos" (sections) que aparecen con suaves transiciones y revelan el mensaje poco a poco.

Botón "No" Escurridizo: Un toque divertido e interactivo. Si el usuario intenta hacer clic o tocar el botón "No", este esquiva el cursor moviéndose a una posición aleatoria en la pantalla. Además, el botón "Sí" crece ligeramente con cada intento fallido.

Efectos Especiales: Al hacer clic en el "Sí", la galaxia se acelera y se emite una pequeña explosión de partículas en la pantalla para celebrar.

Totalmente Responsivo: Diseñado para verse bien tanto en dispositivos móviles como en pantallas de escritorio.

🛠️ Tecnologías Utilizadas

HTML5: Estructura semántica de la página.

CSS3: Variables nativas (:root), Flexbox, animaciones de fotogramas clave (@keyframes), diseño adaptativo y compatibilidad con modo oscuro/claro.

JavaScript (Vanilla):

Uso de la API de Canvas para la renderización de partículas.

Lógica para el manejo de eventos (clics, hover, touch) y el comportamiento dinámico del botón de rechazo.

📦 Instalación y Uso

Este proyecto no requiere de ningún servidor, base de datos ni dependencias externas. Funciona directamente en el navegador.

Descarga los archivos: Guarda el código principal en un archivo llamado index.html.

Agrega la fotografía:

Crea una carpeta llamada img en el mismo directorio donde está tu index.html.

Coloca dentro la foto que deseas mostrar al final y nómbrala galaxiaimagen.jpg.

(Nota: Si la imagen no se encuentra, el marco simplemente se ocultará sin romper el diseño gracias al atributo onerror).

Ejecutar: Simplemente haz doble clic en index.html para abrirlo en tu navegador web (Chrome, Firefox, Safari, Edge, etc.).

📂 Estructura de Archivos recomendada

/
├── index.html            # El archivo principal con todo el código (HTML, CSS, JS)
└── img/
    └── galaxiaimagen.jpg # La imagen que aparece al dar el "Sí"


🎨 Posibles Personalizaciones

Si deseas adaptar este proyecto para alguien más o cambiar el estilo, busca estas secciones en el archivo index.html:

Textos y Nombres: Puedes buscar "Naomy" en el HTML y reemplazarlo. Modifica los textos de los <p> y <h1> según tu mensaje.

Colores (CSS): En la etiqueta <style>, dentro de :root, puedes cambiar variables como --accent (rosado), --violet (violeta) o --gold (dorado) para darle otra paleta de colores a los textos y botones.

Textos de los botones: En el array labels y notes dentro de la etiqueta <script>, puedes personalizar los divertidos mensajes que aparecen cuando se intenta presionar el botón "No".

Creado con mucho cariño por ElmoElMalcriado (tu Dibujito malcriado) - 2026
