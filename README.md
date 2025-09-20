# SALOMON-RAMIREZ-PROYECTO-AMIGO-SECRETO
ESTE ESTA ES LA ULTIMA VERSION DE MI PROYECTO REALIZE ALGUNOS CAMBIOS A LOS ARCHIVOS BASE 
# 🏆 Challenge ONE | Amigo Secreto - Sorteador Neon Refactorizado

Este proyecto fue desarrollado como parte del programa **Oracle Next Education (ONE)** de **Alura Latam**, específicamente para el **Challenge Amigo Secreto**.

El objetivo principal de esta versión fue la **refactorización y el diseño**, transformando un código base funcional en una interfaz moderna, implementando la temática **"Electric Dark Neon"** de alto impacto visual y solucionando problemas de visibilidad de recursos.

---

## 👨‍💻 Desarrollador

* **Nombre:** Salomon Ramirez Ortega
* **Programa:** Oracle Next Education (ONE) | Alura Latam

---

## ✨ Contribuciones y Logros Técnicos

Este proyecto demuestra competencias en el manejo de la lógica de JavaScript y la implementación de diseño avanzado con CSS (Layout y Estilismo Neon).

| Área | Contribución Clave de la Refactorización |
| :--- | :--- |
| **Diseño y Tema** | Implementación completa del **Tema Neon** (fondo oscuro, acentos Cian Eléctrico y Fucsia), utilizando **variables CSS** y `box-shadow` para generar los efectos de brillo característicos. |
| **Layout y Proporciones** | Ajuste de la estructura CSS (Flexbox) para balancear las proporciones y el espaciado entre el encabezado, la imagen principal y la sección de entrada, logrando un diseño limpio y moderno. |
| **Visibilidad de Recursos** | **Corrección crítica de la visibilidad** de las imágenes (`amigo-secreto.png` y `play_circle_outline.png`) que se perdían en el fondo oscuro, asegurando que los íconos contrasten correctamente con los botones de neón. |
| **Funcionalidad (UX/UI)** | Integración completa del botón **"Reiniciar"** (`reiniciarSorteo()`) y aplicación de un borde de neón al `input-wrapper` para enmarcar la entrada de nombres de manera visualmente atractiva. |

---

## 🛠️ Estructura del Código

El proyecto mantiene una estructura simple de desarrollo web, con los siguientes archivos clave:

| Archivo | Rol | Tecnologías |
| :--- | :--- | :--- |
| **`index.html`** | Estructura & Contenido | HTML5. |
| **`style.css`** | Presentación & Diseño | CSS3, **Variables CSS**, Flexbox, Efectos Neón. |
| **`app.js`** | Lógica Central | JavaScript (Manejo de DOM, Validación, Algoritmo de Sorteo). |

### ⚙️ Lógica Principal (`app.js`)

El archivo `app.js` maneja el estado del sorteo a través del array global `amigos` y las funciones de control:

1.  **`agregarAmigo()`:** Gestiona la entrada de nombres, validando que no estén vacíos y que no estén duplicados (ignorando mayúsculas/minúsculas).
2.  **`sortearAmigo()`:** Ejecuta el sorteo, **verificando que haya un mínimo de 2 participantes** antes de seleccionar y mostrar un ganador al azar.
3.  **`reiniciarSorteo()`:** Limpia completamente el array de participantes y actualiza la interfaz, restableciendo la aplicación a su estado inicial.

---

## 🚀 Instalación y Ejecución

1.  **Requisitos:** Solo necesitas un navegador web moderno (Chrome, Firefox, etc.).
2.  **Ejecución:** Abre el archivo **`index.html`** directamente en tu navegador para interactuar con la aplicación.
