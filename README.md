<div align="center">
  <img src="./assets/logo.svg" alt="Logo del Proyecto" width="200">
  <br/>
  <h1>
    <b>Calculadora de Convolución</b>
  </h1>
  <p>
    Una herramienta web interactiva para calcular y visualizar la convolución de dos señales. Defina las funciones, observe el desplazamiento y analice la gráfica resultante en tiempo real.
  </p>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-%3E%3D20-8A2BE2?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js version requirement">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-9370DB?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/License-MIT-9370DB?style=for-the-badge" alt="License MIT">
</div>

---

## 📜 Descripción del Proyecto

Este proyecto nace como una herramienta educativa y de análisis para la materia de **Procesamiento Digital de Señales**. Su propósito es desmitificar la operación de **convolución** al permitir a los usuarios visualizar cómo la forma de una señal modifica la forma de otra.

La aplicación permite definir dos señales, una fija y una que se desplazará. Calcula la integral de convolución y muestra de forma simultánea tres gráficas clave: la señal fija, la señal en desplazamiento y la función resultante de la convolución, facilitando la comprensión intuitiva de este concepto fundamental en el procesamiento de señales.

---

## ✨ Características Principales

* **Definición Flexible de Señales:** Permite definir las dos señales a convolucionar, ya sea seleccionándolas de un menú de funciones predefinidas o introduciendo manualmente sus ecuaciones, periodos e intervalos.
* **Cálculo de la Ecuación:** El programa determina y muestra la ecuación matemática resultante de la operación de convolución.
* **Visualización en Tiempo Real:** Muestra tres gráficas simultáneas para un análisis completo:
    1.  **Gráfica de la señal fija.**
    2.  **Gráfica de la señal que se desplazará.**
    3.  **Gráfica de la convolución resultante.**
* **Claridad en las Gráficas:** Todas las visualizaciones se presentan con sus respectivos títulos y nombres en los ejes para una interpretación clara.
* **Previsualización en LaTeX:** Observa en tiempo real la representación matemática de las funciones que estás introduciendo.

---

## 🛠️ Tecnologías Utilizadas

Este proyecto fue refactorizado de un monolito a una arquitectura moderna utilizando:

* **Vite:** Como servidor de desarrollo y empaquetador, ofreciendo Hot Module Replacement (HMR).
* **Tailwind CSS v4:** Para un estilizado rápido y mantenible a través de su motor de plugins en Vite.
* **Plotly.js:** Para la renderización de las gráficas interactivas.
* **Math.js:** Para el parseo de expresiones matemáticas y la generación de LaTeX.
* **MathJax:** Para el renderizado de alta calidad de las fórmulas LaTeX en el DOM.

---

## 🚀 Instalación y Puesta en Marcha

Para ejecutar este proyecto en tu entorno local, sigue estos sencillos pasos.

### **Pre-requisitos**

Asegúrate de tener instalada una versión de **Node.js 20 o superior**.

```bash
node -v
# Debería mostrar v20.x.x o superior
````

### **Pasos de Instalación**

1.  **Clona el repositorio** en tu máquina local:

    ```bash
    git clone https://github.com/eddndev/fourier-transform.git
    ```

2.  **Navega al directorio** del proyecto:

    ```bash
    cd fourier-viewer
    ```

3.  **Instala las dependencias** del proyecto con npm:

    ```bash
    npm install
    ```

4.  **Inicia el servidor de desarrollo** de Vite:

    ```bash
    npm run dev
    ```

¡Y listo\! La aplicación estará disponible en `http://localhost:5173` (o el puerto que indique Vite en tu terminal).

-----

## 👥 Equipo

Este proyecto fue desarrollado por el **Equipo 1 - Procesamiento Digital de Señales**.

| \# | Integrante                    |
| :-: | :---------------------------- |
| 1 | `Alonso Sánchez Eduardo`        |
| 2 | `Bonilla Ramírez Josué Eleazar` |
| 3 | `Jiménez Meza Ana Harumi`       |
| 4 | `Quiroz Mora Abel Mauricio`     |
| 5 | `Vilchis Paniagua Johan Emiliano` |

-----

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.