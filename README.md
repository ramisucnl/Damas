# 🔴 Damas AI Elite - Pro Edition 🔵

¡Bienvenido a **Damas AI UCNL**, una versión moderna, fluida y potente del clásico juego de damas! Este proyecto está construido enteramente con **React.js** y **Tailwind CSS**, ofreciendo una experiencia de usuario enriquecida con sonidos, animaciones y una Inteligencia Artificial con tres niveles de dificultad.

![Damas Screenshot](https://img.shields.io/badge/Status-Desarrollo_Finalizado-brightgreen)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Características Principales

-   **👑 Reinas Voladoras:** Implementación fiel de las reglas internacionales donde las reinas se desplazan largas distancias en diagonal.
-   **🤖 Inteligencia Artificial:** Tres niveles de desafío (Aprendiz, Estratega y Maestro) con un motor de evaluación heurística.
-   **🔊 Experiencia Inmersiva:** Efectos de sonido para movimientos, capturas y coronaciones.
-   **🎨 Diseño Premium:** Interfaz limpia con gradientes, sombras dinámicas y animaciones de "brillo" para las piezas clave.
-   **⚖️ Reglas Refinadas:** -   Los peones solo capturan hacia adelante.
    -   Las Reinas pueden capturar en cualquier dirección.
    -   Obligatoriedad de captura si existe un movimiento disponible.

## 🕹️ Cómo Jugar

1.  **Selección:** Haz clic en una de tus piezas rojas. Si hay una captura obligatoria, el juego resaltará la pieza que debe moverse.
2.  **Movimiento:** Los cuadros disponibles se marcarán con un círculo verde animado.
3.  **Coronación:** Llega al extremo opuesto para convertir tu peón en Reina y desbloquear el movimiento de "vuelo".
4.  **Victoria:** Elimina todas las piezas de la CPU o bloquea sus movimientos.

## 🛠️ Tecnologías Utilizadas

-   **React 18:** Manejo de estados complejos y renderizado eficiente del tablero.
-   **Tailwind CSS:** Diseño responsivo y estilización moderna sin archivos CSS externos.
-   **Babel Standalone:** Permite ejecutar el código JSX directamente en el navegador.
-   **Mixkit SFX:** Biblioteca de sonidos para una respuesta táctil auditiva.

## 🚀 Instalación y Uso

No necesitas configurar un entorno de desarrollo complejo ni instalar dependencias de Node.js. Al ser una aplicación **Single File**, puedes ejecutarla de la siguiente manera:

1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/damas-ai-elite.git](https://github.com/tu-usuario/damas-ai-elite.git)
    ```
2.  Navega a la carpeta del proyecto.
3.  Abre el archivo `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge).

## 🧠 Lógica de la IA

El nivel **Maestro** utiliza un motor de evaluación que analiza:
-   **Valor de Material:** Las reinas valen el doble que los peones.
-   **Posicionamiento:** Los peones ganan valor a medida que se acercan a la línea de coronación.
-   **Agresividad:** Prioriza capturas múltiples y el control del centro del tablero.

## 🤝 Contribuciones

¡Las sugerencias son bienvenidas! Si tienes ideas para mejorar la IA (como implementar el algoritmo Minimax con profundidad) o añadir un modo multijugador online, siéntete libre de hacer un fork y enviar un Pull Request.

---
Desarrollado con ❤️ por [Ramiro Eliab Guajardo Garza], Como práctica de la materia de Programación WEB con IA. IA utilizada: Gemini
