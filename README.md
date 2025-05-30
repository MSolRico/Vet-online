Documentación Técnica del Proyecto Vet Online

1. Introducción
Vet Online es una página web responsiva destinada a facilitar el registro y gestión básica de mascotas para una veterinaria. Incluye una interfaz amigable, formulario para ingresar datos de mascotas, un popup para inicio de sesión y una sección de contacto.

2. Tecnologías Utilizadas
HTML5: Estructura semántica de la página.

CSS3: Estilos y diseño responsivo.

JavaScript: Funcionalidades interactivas (menú móvil, popup login, smooth scroll).

FontAwesome: Iconos vectoriales para UI.

Formspree: Servicio para manejo de formularios y envío de emails sin backend.

GitHub Pages: Hosting gratuito para publicar la web.

3. Estructura del Proyecto
/
├── index.html       # Archivo principal HTML
├── style.css        # Estilos CSS
├── Fotos/           # Carpeta con imágenes (logo, fotos para la web)
└── README.md        # Documentación técnica

4. Descripción de las Secciones
4.1 Navegación
Barra fija con logo y enlaces a secciones internas: Inicio, Formulario, Contacto.

Menú hamburguesa para versión móvil, que despliega links.

Enlaces con smooth scroll para mejor experiencia.

4.2 Sección Hero (Bienvenida)
Título principal y una imagen decorativa.

Diseño centrado y responsivo.

4.3 Formulario de Registro de Mascotas
Campos obligatorios: Tipo de mascota (radio), Nombre, Apodo, Edad, Descripción física.

Campos opcionales: Sexo, Color principal (desplegable), Características (texto libre).

Campo para subir fotos múltiples (input file).

Botón para enviar formulario a Formspree.

Botón para abrir popup de login.

4.4 Popup de Inicio de Sesión
Formulario simple con usuario y contraseña.

Aparece/desaparece al hacer clic en el botón.

Se cierra al hacer clic fuera del popup.

4.5 Footer (Pie de Página)
Información de contacto con iconos: teléfono y mail.

Texto legal y copyright.

5. Diseño Responsivo
Uso de media queries para adaptar tamaños de fuente y botones en móviles (ejemplo: max-width 480px).

Menú hamburguesa visible en pantallas pequeñas.

Botones y formularios con ancho completo en móviles para facilitar interacción táctil.

6. Funcionalidades JavaScript
Menú toggle: Al hacer clic en ícono hamburguesa muestra u oculta menú.

Smooth scrolling: Transición suave al hacer clic en enlaces de navegación.

Popup login: Función toggleLogin() para mostrar u ocultar popup.

Cerrar popup clic fuera: Detecta clic fuera del popup para cerrarlo automáticamente.

7. Configuración del Formulario
El formulario envía los datos a Formspree para su procesamiento.

Método POST y acción con URL de Formspree.

Campos marcados con * son obligatorios y usan validación HTML5 básica.

Campo de tipo archivo permite múltiples imágenes (limitado por el navegador).

8. Instrucciones para Despliegue y Uso
8.1 Uso local
Descargar o clonar el repositorio.

Abrir el archivo index.html en cualquier navegador moderno.

Se recomienda conexión a internet para cargar iconos FontAwesome y enviar formularios.

8.2 Publicación en GitHub Pages
Subir todo el proyecto a un repositorio público en GitHub.

Ir a la configuración del repositorio.

En la sección Pages, seleccionar la rama principal (main o master) y la carpeta raíz.

Guardar cambios y esperar que GitHub genere la URL.

9. Enlace al Sitio Web
El proyecto está disponible en línea a través de GitHub Pages:

🔗 Sitio en vivo:
https://msolrico.github.io/Vet-online/

10. Consideraciones y Mejoras Futuras
Validaciones de formulario más avanzadas con JavaScript.

Autenticación real en el login con backend (actualmente solo UI).

Guardado y gestión de imágenes y datos en servidor.

Sección de administración para mascotas registradas.

Adaptación y optimización para accesibilidad.

Mejoras en diseño visual y UX.

11. Recursos y Créditos
Iconos de FontAwesome: https://fontawesome.com

Servicio Formspree: https://formspree.io

Imágenes enviadas por el profesor.

Inspiración y diseño basado en el boceto enviado por el profesor y prácticas modernas de desarrollo web.