# 🤖 Plataforma Interactiva: Reglamento Oficial Torneo SumoBot

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>

<br>

## 📖 Descripción General
Esta es una plataforma web educativa e interactiva diseñada para presentar de manera dinámica y atractiva el **Reglamento Técnico y Deportivo Oficial del Torneo de Robótica modalidad SumoBot**, organizado por **TecnoAcademia / SENA**. 

El proyecto reemplaza el formato tradicional de lectura en PDF por un sistema de aprendizaje modular gamificado. Los competidores deben completar diferentes capítulos (módulos), superar pequeñas pruebas de conocimiento (quizzes) para confirmar su entendimiento y así ir desbloqueando progresivamente el resto del contenido.

## 🚀 Acceso al Proyecto
Puedes visualizar la plataforma en vivo aquí:
👉 https://altarians05.github.io/ReglamentoSumoBot/index.html

## ✨ Características Principales
*   **Diseño Institucional:** Interfaz gráfica adaptada a la paleta de colores oficial del SENA (Verde, Azul, Naranja, Amarillo) utilizando fuentes tipográficas modernas (Montserrat, Roboto).
*   **Sistema de Progreso:** Los módulos se encuentran inicialmente bloqueados. A medida que el usuario aprueba cada sección, la barra de progreso avanza y se habilita el acceso al siguiente nivel. Todo el avance se gestiona temporalmente mediante `sessionStorage` para mantener la fluidez en la navegación.
*   **Quizzes Interactivos:** Cada módulo incluye un pequeño desafío o cuestionario de selección múltiple que valida la comprensión de las reglas (ej. Roles del Capitán, especificaciones del Dohyo).
*   **Integración de Documentos:** Cuenta con botones de acceso rápido para consultar o descargar el manual completo en PDF sin salir de la experiencia principal.
*   **Diseño Responsivo:** Visualización optimizada tanto para pantallas de escritorio como para dispositivos móviles.

## 📂 Estructura del Proyecto

```text
📁 Proyecto-SumoBot-SENA/
├── 📄 index.html             # Menú principal (Tablero de Control / Centro de Comando)
├── 📄 modulo0.html           # Módulo 1: Disposiciones Generales
├── 📄 modulo1.html           # Módulo 2: Especificaciones Técnicas (Ejemplo)
├── 📁 imagenes/              # Carpeta de recursos gráficos
│   ├── 📁 Logos/             # Logos institucionales (SENA, TecnoAcademia)
│   └── 📁 Fondos/            # Banners y elementos visuales
└── 📁 Reglamento Virtual SumoBot/
    └── 📁 documentos/
        └── 📄 REGLAMENTO OFICIAL DE COMPETENCIA TORNEO SUMOBOT.pdf
```

## 🚀 Instalación y Uso
El proyecto no requiere la instalación de dependencias, frameworks, ni servidores backend o bases de datos complejas. Está construido 100% en tecnologías frontend nativas (Vanilla JS).

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/sumobot-reglamento-sena.git
    ```
2.  **Preparar los recursos:**
    Asegúrate de que el archivo PDF del manual se encuentre en la ruta correcta: `Reglamento Virtual SumoBot/documentos/` para que los botones de descarga funcionen apropiadamente.
3.  **Ejecutar el proyecto:**
    Al ser un proyecto estático, basta con abrir el archivo `index.html` en tu navegador web de preferencia (Google Chrome, Mozilla Firefox, Microsoft Edge).

## 🛠️ Tecnologías Utilizadas
*   **HTML5:** Estructuración semántica de cada módulo y del menú principal.
*   **CSS3:** Estilos personalizados, variables de color CSS (`--sena-blue`, `--sena-green`, etc.), animaciones y diseño responsivo sin depender de librerías externas.
*   **JavaScript (ES6):** Control de los eventos del usuario, lógica de los quizzes, sistema de validación de respuestas y manejo del estado a través de la API `sessionStorage` del navegador.
*   **FontAwesome:** Íconos vectoriales para enriquecer visualmente la interfaz.
*   **Google Fonts:** Fuentes *Montserrat* (para títulos) y *Roboto* (para textos).

## 🤝 Contribuciones
Este proyecto fue desarrollado para uso formativo e institucional de la comunidad SENA. Si deseas proponer mejoras, corregir errores o expandir el material:
1. Haz un *Fork* del repositorio.
2. Crea una rama para tu característica (`git checkout -b feature/NuevaCaracteristica`).
3. Realiza tus cambios y haz *commit* (`git commit -m 'Añade nueva característica'`).
4. Sube la rama (`git push origin feature/NuevaCaracteristica`).
5. Abre un *Pull Request*.

---
*Desarrollado para el fortalecimiento de habilidades STEM mediante la robótica competitiva.*
