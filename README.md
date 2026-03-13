 # 🚀 TaskFlow Pro - Bootcamp Project

Este es el proyecto final de la fase inicial del bootcamp, enfocado en crear una aplicación de gestión de tareas profesional utilizando **JavaScript nativo**, **Tailwind CSS** y persistencia de datos.

---

## 🎨 1. Planificación y Diseño (Punto 2)

Antes de programar, se planificó la interfaz buscando un diseño limpio, funcional y responsivo.

- **Secciones:** Cabecera dinámica, panel lateral de estadísticas, formulario de entrada y lista de tareas con filtros.
- **Acciones:** Añadir, editar, completar y eliminar tareas.
- **Wireframe:** Puedes encontrar el diseño inicial en la carpeta `docs/design`.

## 🛠️ 2. Tecnologías Utilizadas

- **HTML5 Semántico:** Estructura clara para SEO y accesibilidad.
- **Tailwind CSS:** Diseño moderno basado en clases de utilidad.
- **JavaScript (ES6+):** Lógica dinámica, filtrado de datos y manipulación del DOM.
- **LocalStorage:** Persistencia de datos para que las tareas no se borren al recargar.

## 🌗 3. Funcionalidades Destacadas (Puntos 8 y 9)

- **Modo Oscuro:** Soporte nativo que se activa con un botón y guarda la preferencia del usuario.
- **Filtros Avanzados:** Visualización de tareas "Todas", "Pendientes" o "Completadas".
- **Búsqueda en tiempo real:** Encuentra tareas rápidamente mediante el buscador integrado.
- **Estadísticas dinámicas:** Contador automático de tareas totales y estados.

## 🧪 4. Testing Manual (Punto 10)

Se realizaron las siguientes pruebas para asegurar la calidad:

| Caso de Prueba | Resultado | Observaciones |
| :--- | :--- | :--- |
| Añadir tarea vacía | ✅ Correcto | El navegador impide el envío por el atributo `required`. |
| Recarga de página | ✅ Correcto | Las tareas persisten gracias a LocalStorage. |
| Modo Oscuro | ✅ Correcto | El tema se mantiene tras recargar la web. |
| Filtros | ✅ Correcto | Los filtros separan correctamente las tareas hechas de las pendientes. |
| Edición | ✅ Correcto | El prompt permite cambiar el título sin perder el ID. |

## ♿ 5. Accesibilidad (Punto 11)

- Se han incluido atributos `aria-label` en botones de iconos.
- La navegación es posible mediante teclado (Tabulador).
- Contraste de colores verificado para facilitar la lectura.

## 🚀 6. Despliegue (Punto 12)

La aplicación está desplegada y disponible en el siguiente enlace:

👉 **[PEGA AQUÍ TU ENLACE DE VERCEL]**
https://task-master-pro-roan.vercel.app
---
*Desarrollado como proyecto educativo para el Bootcamp.*
