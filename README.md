# dudas-WEB

PREGUNTASWEB
Sistema de Encuestas - CETIS 61
¡Bienvenido! Este es un proyecto de aplicación web desarrollado en Python utilizando el micro-framework Flask. El objetivo principal es recopilar las dudas e inquietudes de la comunidad escolar (alumnos, padres de familia, aspirantes y comunidad en general) respecto al plantel CETIS 61, almacenando las respuestas de forma segura en una base de datos en la nube.

Características Clave
Selección de Perfil: Permite segmentar las respuestas según el tipo de usuario (Alumno, Padre de Familia, etc.).
Flujo Dinámico: El usuario puede registrar múltiples dudas consecutivas.
Cambio de Rol en Caliente: Incluye una opción para regresar al inicio y registrar dudas desde la perspectiva de otro perfil sin perder las dudas que ya se habían escrito en la sesión actual.
Persistencia en la Nube: Conexión directa y almacenamiento en tiempo real en MongoDB Atlas.
Diseño Responsivo: Interfaz limpia, minimalista y adaptada para dispositivos móviles mediante CSS integrado.
Tecnologías Utilizadas
Backend: Python 3 (Flask)
Base de Datos: MongoDB Atlas (NoSQL)
Librerías de Python: pymongo, dnspython, gunicorn (para el despliegue)
Frontend: HTML5 y CSS3 (Renderizado dinámico mediante Jinja2 con render_template_string)
