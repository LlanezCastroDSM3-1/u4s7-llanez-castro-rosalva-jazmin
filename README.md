# U4S8 — Llanez Castro Rosalva Jazmin

<!-- sección con la URL pública de Render -->
## Demo en vivo (producción)
<!-- tu dirección real de Render de esta práctica -->
https://u4s8-llanez-castro-rosalva-jazmin.onrender.com

<!-- sección que explica el proyecto a quien lo visite -->
## Qué hace este proyecto
Este proyecto es una plataforma web interactiva diseñada como una vitrina de servicios profesionales. Permite a los usuarios explorar un catálogo público de servicios con funciones avanzadas de búsqueda y paginación, así como gestionar sus propios servicios mediante una interfaz intuitiva.

El sistema cuenta con un panel de administración y un flujo completo de autenticación que permite a los usuarios registrarse, iniciar sesión y realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre sus publicaciones de forma segura y personalizada.

<!-- sección con las tecnologías usadas -->
## Stack técnico
<!-- las 4 herramientas del curso -->
Django + MySQL (Aiven) + Tailwind CSS + Render

<!-- sección con la prueba de seguridad de la Semana 6 -->
## Cómo se prueba el aislamiento por usuario
Demo en vivo (produccion)
https://u3s6-llanez-castro-rosalva-jazmin.onrender.com/servicios/

Semana 6 — Autenticacion, sesiones y seguridad
Registro/login/logout propios; cada usuario ve y edita solo

sus propios servicios (probado con usuario_a y usuario_b).

Prueba de aislamiento
Se hicieron pruebas intentando entrar a los servicios de otro usuario mediante un enlace directo, usando una cuenta que no tenía acceso a ese link. La idea era comprobar si se podía entrar o modificar información que no correspondía a esa cuenta. Con las pruebas se revisó que cada usuario pudiera acceder solamente a sus propios servicios. Esto ayudó a comprobar que el sistema tuviera un poco más de seguridad entre las cuentas.

<!-- sección con el recorrido del curso -->
## Historial de unidades
<!-- Unidad 1 -->
- Unidad 1: portafolio estático con HTML5 + Tailwind
<!-- Unidad 2 -->
- Unidad 2: modelo Servicio migrado a MySQL, deploy dinámico en Render
<!-- Unidad 3 -->
- Unidad 3: CRUD completo con ModelForms + autenticación y sesiones
<!-- Unidad 4 -->
- Unidad 4: paginación, búsqueda, UI review y defensa final