# 🎮 Hub de Desarrollo & Blog Personal - Tiago Caranchi

Este repositorio contiene una plataforma web estática desarrollada para la **UNTDF**, centrada en la integración de diseño responsivo y estándares de accesibilidad moderna.

## 🕹️ Guía de Ejecución

El proyecto está construido sobre una arquitectura *serverless* y estática, por lo que su despliegue es inmediato.

* **Despliegue Local Rápido**
    * Descargar el código fuente en un directorio local.
    * Ejecutar el archivo `index.html` en cualquier navegador moderno.
* **Entorno de Desarrollo Federado**
    * Abrir el espacio de trabajo en **VS Code**.
    * Se recomienda el uso de la extensión **Live Server** para previsualizar cambios en tiempo real mediante el servidor local.

## 📂 Organización del Directorio

* **`index.html`**: Punto de entrada al blog. Presenta el ecosistema de campeones (Jhin, Kai'Sa, Vayne) y galerías dinámicas.
* **`about.html`**: Perfil profesional y hoja de ruta académica (Ingeniería a Sistemas/Astronomía). Contiene el desglose de *stack* tecnológico.
* **`contact.html`**: Interfaz de comunicación con protocolos de validación de datos en tiempo real.
* **`assets/`**:
    * **`styles.css`**: Motor de estilos personalizado con arquitectura de variables y efectos de profundidad.
    * **`images/`**: Repositorio de recursos multimedia, branding y activos visuales.

## ⚙️ Especificaciones Técnicas y Stack

* **Maquetado Semántico (HTML5)**: Implementación de etiquetas estructurales (`<nav>`, `<main>`, `<aside>`) para optimizar el SEO y la lectura del DOM.
* **Diseño Estético Avanzado (CSS3)**:
    * **Gestión de Estados**: Control de flujo visual mediante variables `:root`.
    * **Feedback de Usuario**: Lógica visual basada en pseudoclases `:valid` e `:invalid` para una interacción intuitiva en formularios.
    * **Procesamiento Visual**: Uso de filtros de desenfoque gaussianos y transiciones de aceleración suave (`ease-in-out`).
* **Framework de Estilos (Bootstrap 5)**: Utilizado como base para el sistema de rejilla flexible, componentes de navegación persistente (`sticky`) y visualizadores de imágenes.
* **Estándares de Accesibilidad (A11y)**:
    * Atributos ARIA para una navegación asistida inclusiva.
    * Estructura de encabezados secuencial para una correcta indexación semántica.