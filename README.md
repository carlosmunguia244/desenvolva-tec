# Desemvolvatec

Una plataforma web interactiva diseñada para ayudar a los estudiantes universitarios a gestionar su estrés académico, organizar sus rutinas y conectar con una comunidad de apoyo emocional y orientación.

 **[Visita el proyecto en vivo aquí](https://carlosmunguia244.github.io/desenvolva-tec/)**

## Características Principales (Features)

* Autenticación Segura:** Sistema de registro y login integrado con Firebase Authentication, incluyendo verificación de identidad por correo electrónico y rutas protegidas.
* Dashboard Interactivo:** Panel de control personalizado que lee datos dinámicos del usuario y calcula en tiempo real su nivel de resiliencia y manejo de estrés.
* Asesoría Virtual (Simulación IA):** Interfaz de chat asíncrona que simula conversaciones de orientación vocacional y emocional con tiempos de respuesta naturales.
* Gestor de Rutinas Inteligente:** Sistema de checklist y tareas ponderadas (Carga Baja, Media, Alta) que guardan el progreso del estudiante en `localStorage` vinculado a su ID de usuario.
* Comunidad y Talleres:** Sección interactiva con pestañas (Tabs) para explorar grupos de estudio, talleres oficiales y permitir la publicación de nuevas salas virtuales.
* Diseño Responsivo:** Interfaz adaptable a dispositivos móviles (Mobile-First) con menús laterales colapsables, notificaciones tipo "Dropdown" y modales.

## Tecnologías Utilizadas (Stack)

* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, CSS Grid), Vanilla JavaScript (ES6, Async/Await, Promesas).
* **Backend as a Service (BaaS):** Firebase (Authentication).
* **Seguridad:** API Keys con restricciones de referenciadores HTTP (HTTP referrers) desde Google Cloud Console.
* **Despliegue:** GitHub Pages.
* **Herramientas de correo:** FormSubmit (Integración de formularios sin backend propio).

## Instalación y Uso Local

Si deseas correr este proyecto en tu entorno local para hacer modificaciones:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/carlosmunguia244/desenvolva-tec.git](https://github.com/carlosmunguia244/desenvolva-tec.git)