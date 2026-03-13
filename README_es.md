# 🎨 Temas CSS Elegantes para el Visor de Calibre

## [🇬🇧 English](README.md) | 🇪🇸 Español

¡Transforma tu experiencia de lectura en Calibre! ✨

Este repositorio contiene una hoja de estilos CSS unificada que ofrece tres temas estéticos y elegantes para el visor de libros electrónicos de Calibre. Diseñados para ser agradables a la vista, modernos y altamente legibles, especialmente en monitores de alta resolución.

---

## ✨ Características Principales

*   🌓 **Modo Dual Automático:** Se adapta perfectamente a los esquemas de color claro y oscuro de Calibre sin necesidad de cambiar el código.
*   🎨 **Tres Temas Cuidadosamente Diseñados:** Elige entre "Clásico Moderno", "Elegante Profesional" o "Minimalista Cálido" para que coincida con tu estado de ánimo.
*    offline: **Fuentes Locales:** Utiliza las fuentes instaladas en tu sistema para un rendimiento rápido y sin necesidad de conexión a internet.
*   👓 **Enfocado en la Legibilidad:** Tipografía y espaciado optimizados para reducir la fatiga visual durante largas sesiones de lectura.
*   🔧 **Fácil de Personalizar:** Cambia entre temas o ajusta los colores a tu gusto editando unas pocas líneas.

---

## 📸 Vista Previa

_Aquí puedes colocar una captura de pantalla que muestre cómo se ven los temas en tu Calibre. ¡Una imagen vale más que mil palabras!_ (Las variaciones de entre fuentes y estilo, no de colores, son muy sutiles de percibir)
### Noche 🌓 (Tema 1: Tema 1: El Clásico Moderno)
<img width="1507" height="1124" alt="imagen" src="https://github.com/user-attachments/assets/d760912f-6f86-48c4-9446-b3aca797d7d3" />

### Noche 🌓 (Tema 2: El Elegante Profesional)
<img width="1501" height="1077" alt="calibre-parallel_fpHAkbftqO" src="https://github.com/user-attachments/assets/db81d5af-af1b-4afb-8c86-0239ffe2d3f0" />

### Noche 🌓 (Tema 3: El Minimalista Cálido)
<img width="1505" height="1120" alt="imagen" src="https://github.com/user-attachments/assets/6f925350-a506-4ddd-967d-242895cf14b9" />


### Dia ☀️ (Tema 1: Tema 1: El Clásico Moderno)
<img width="1497" height="1116" alt="calibre-parallel_JqLHzsCzc5" src="https://github.com/user-attachments/assets/cd1ca501-1d27-43b6-938f-6ba3ae3b8101" />

### Dia ☀️ (Tema 2: El Elegante Profesional)
<img width="1499" height="1119" alt="imagen" src="https://github.com/user-attachments/assets/697e49ef-6d02-4ff5-97cd-d9d34ee7f8c1" />

### Dia ☀️ (Tema 3: El Minimalista Cálido)
<img width="1515" height="1127" alt="imagen" src="https://github.com/user-attachments/assets/1021327c-bc27-4fe6-b4c6-2c0caeb2d604" />

### Comparación visual
<img width="1199" height="534" alt="image" src="https://github.com/user-attachments/assets/6a63ba5c-32ac-4165-ac55-e0cad8cec6c8" />



---

## 🖋️ Requisitos

Para que los temas funcionen correctamente, necesitas tener **Calibre** instalado y las siguientes familias de fuentes en tu sistema operativo. Todas son gratuitas y de código abierto.

#### Tema 1: El Clásico Moderno
*   [Literata (Google Fonts)](https://fonts.google.com/specimen/Literata)
*   [Inter (Google Fonts)](https://fonts.google.com/specimen/Inter)

#### Tema 2: El Elegante Profesional
*   [Spectral (Google Fonts)](https://fonts.google.com/specimen/Spectral)
*   [IBM Plex Sans (Google Fonts)](https://fonts.google.com/specimen/IBM+Plex+Sans)

#### Tema 3: El Minimalista Cálido
*   [Alegreya (Google Fonts)](https://fonts.google.com/specimen/Alegreya)
*   [Lato (Google Fonts)](https://fonts.google.com/specimen/Lato)

---

## 🚀 Cómo Usarlo

### Opcion 1 (facil)
1.  **Instala las fuentes** de al menos el tema que desees utilizar (aunque se recomienda instalar todas).
2.  Descarga el archivo `calibre-viewer-theme-number-1` de este repositorio, y elige segun el tema que te guste.
    - number-1 para el Tema 1: El Clásico Moderno
    - number-2 para el Tema 2: El Elegante Profesional
    - number-3 para el Tema 3: El Minimalista Cálido
3.  Abre cualquier libro en el **Visor de libros electrónicos** de Calibre.
4.  Haz clic en el icono de **Preferencias** (⚙️ o un martillo).
5.  Ve a la pestaña **Estilos**.
6.  Copia y pega **todo el contenido** del archivo, Haz clic en Aplicar y ¡listo!, Recarga el libro y disfruta !




### Opcion 2 (manual)

1.  **Instala las fuentes** de al menos el tema que desees utilizar (aunque se recomienda instalar todas).
2.  Descarga el archivo `calibre-viewer-themes-all-in-one.css` de este repositorio.
3.  Abre cualquier libro en el **Visor de libros electrónicos** de Calibre.
4.  Haz clic en el icono de **Preferencias** (⚙️ o un martillo).
5.  Ve a la pestaña **Estilos**.
6.  Copia y pega **todo el contenido** del archivo `calibre-viewer-themes-all-in-one.css` en el cuadro de texto.
7.  **Activa tu tema preferido.** Al final del código, encontrarás una sección llamada `/* --- APLICACIÓN DE FUENTES POR TEMA --- */`. Para activar un tema, simplemente "descoméntalo" (borra los símbolos `/*` y `*/` que lo rodean).

> **¡Importante!** Asegúrate de que solo un tema esté activo (descomentado) a la vez.

Por ejemplo, para activar el **Tema 2**:

**Antes:**
```css
/* TEMA 2: EL ELEGANTE PROFESIONAL */
/*
body { font-family: var(--font-body-elegante); }
h1, h2, h3, h4, h5, h6 { font-family: var(--font-headings-elegante); }
*/
```

Después:
```css
/* TEMA 2: EL ELEGANTE PROFESIONAL */

body { font-family: var(--font-body-elegante); }
h1, h2, h3, h4, h5, h6 { font-family: var(--font-headings-elegante); }
```
Haz clic en Aplicar y ¡listo!, Recarga el libro y disfruta !

🔧 Personalización
Cambiar de Tema (manual)

Puedes cambiar de tema en cualquier momento siguiendo el paso 7 anterior. Recuerda comentar el tema antiguo antes de descomentar el nuevo.

Ajustar los Colores

Todos los colores están definidos como variables CSS al principio del archivo, en la sección :root. Siéntete libre de modificar los valores rgb() para crear tu paleta perfecta.

```css
:root {
    /* Paleta de Colores Claros */
    --bg-light: rgb(245, 241, 233);
    --text-light: rgb(40, 40, 40);
    
    /* Paleta de Colores Oscuros */
    --bg-dark: rgb(25, 25, 30);
    --text-dark: rgb(220, 215, 205);
}
```

🖥️ Tamaño de Fuente Recomendado 

Estos temas brillan especialmente con un tamaño de fuente ligeramente mayor al predeterminado en el visor de Calibre.

Un buen punto de partida en un monitor grande (como un 24") es entre 20 y 22pt. Puedes ajustar esto en (Sugiero que lo cambies desde calibre y no desde el codigo, dentro del libro abierto, debes dar click derecho, Tamaño de letra, y alli aumentas la cantidad)

✍️ Créditos

Diseño y Creación: Gemini 2.5 Pro
