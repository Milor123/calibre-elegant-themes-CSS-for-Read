# 🎨 Elegant CSS Themes for the Calibre Viewer
## 🇬🇧 English | [Español 🇪🇸](README_es.md)


Transform your Calibre reading experience! ✨

This repository contains a unified CSS stylesheet offering three aesthetic and elegant themes for the Calibre E-book Viewer. Designed to be visually pleasing, modern, and highly readable, especially on high-resolution monitors.

---

## ✨ Key Features

*   🌓 **Automatic Dual Mode:** Seamlessly adapts to Calibre's light and dark color schemes without code changes.
*   🎨 **Three Carefully Crafted Themes:** Choose from "Modern Classic," "Professional Elegance," or "Warm Minimalist" to match your mood.
*   offline: **Local Fonts:** Utilizes fonts installed on your system for fast performance and no internet dependency.
*   👓 **Readability Focused:** Optimized typography and spacing to reduce eye strain during long reading sessions.
*   🔧 **Easy to Customize:** Switch between themes or tweak colors to your liking by editing a few lines.

---

## 📸 Preview

_Here you can place a screenshot showcasing how the themes look in your Calibre. A picture is worth a thousand words!_ (The variations in fonts and style, not colors, are very subtle to perceive)
### Night 🌓 (Theme 1: Modern Classic)
<img width="1507" height="1124" alt="image" src="https://github.com/user-attachments/assets/d760912f-6f86-48c4-9446-b3aca797d7d3" />

### Night 🌓 (Theme 2: Professional Elegance)
<img width="1501" height="1077" alt="calibre-parallel_fpHAkbftqO" src="https://github.com/user-attachments/assets/db81d5af-af1b-4afb-8c86-0239ffe2d3f0" />

### Night 🌓 (Theme 3: Warm Minimalist)
<img width="1505" height="1120" alt="image" src="https://github.com/user-attachments/assets/6f925350-a506-4ddd-967d-242895cf14b9" />


### Day ☀️ (Theme 1: Modern Classic)
<img width="1497" height="1116" alt="calibre-parallel_JqLHzsCzc5" src="https://github.com/user-attachments/assets/cd1ca501-1d27-43b6-938f-6ba3ae3b8101" />

### Day ☀️ (Theme 2: Professional Elegance)
<img width="1499" height="1119" alt="image" src="https://github.com/user-attachments/assets/697e49ef-6d02-4ff5-97cd-d9d34ee7f8c1" />

### Day ☀️ (Theme 3: Warm Minimalist)
<img width="1515" height="1127" alt="image" src="https://github.com/user-attachments/assets/1021327c-bc27-4fe6-b4c6-2c0caeb2d604" />

### Visual Comparison
<img width="1200" height="534" alt="image" src="https://github.com/user-attachments/assets/61b53f79-33e4-4800-ad3d-7dc0784b9def" />


---

## 🖋️ Requirements

For the themes to work correctly, you need to have **Calibre** installed and the following font families on your operating system. All are free and open-source.

#### Theme 1: Modern Classic
*   [Literata (Google Fonts)](https://fonts.google.com/specimen/Literata)
*   [Inter (Google Fonts)](https://fonts.google.com/specimen/Inter)

#### Theme 2: Professional Elegance
*   [Spectral (Google Fonts)](https://fonts.google.com/specimen/Spectral)
*   [IBM Plex Sans (Google Fonts)](https://fonts.google.com/specimen/IBM+Plex+Sans)

#### Theme 3: Warm Minimalist
*   [Alegreya (Google Fonts)](https://fonts.google.com/specimen/Alegreya)
*   [Lato (Google Fonts)](https://fonts.google.com/specimen/Lato)

---

## 🚀 How to Use

### Option 1 (Easy)
1.  **Install the fonts** for at least the theme you wish to use (though installing all is recommended).
2.  Download the `calibre-viewer-theme-number-1` file from this repository, choosing based on the theme you like.
    *   number-1 for Theme 1: Modern Classic
    *   number-2 for Theme 2: Professional Elegance
    *   number-3 for Theme 3: Warm Minimalist
3.  Open any book in the Calibre **E-book Viewer**.
4.  Click on the **Preferences** icon (⚙️ or a hammer).
5.  Go to the **Styles** tab.
6.  Copy and paste **the entire content** of the file. Click Apply, and you're done! Reload the book and enjoy!

### Option 2 (Manual)

1.  **Install the fonts** for at least the theme you wish to use (though installing all is recommended).
2.  Download the `calibre-viewer-themes-all-in-one.css` file from this repository.
3.  Open any book in the Calibre **E-book Viewer**.
4.  Click on the **Preferences** icon (⚙️ or a hammer).
5.  Go to the **Styles** tab.
6.  Copy and paste **the entire content** of the `calibre-viewer-themes-all-in-one.css` file into the text box.
7.  **Activate your preferred theme.** At the end of the code, you'll find a section called `/* --- FONT APPLICATION BY THEME --- */`. To activate a theme, simply "uncomment" it (remove the `/*` and `*/` symbols surrounding it).

> **Important!** Ensure only one theme is active (uncommented) at a time.

For example, to activate **Theme 2**:

**Before:**
```css
/* THEME 2: PROFESSIONAL ELEGANCE */
/*
body { font-family: var(--font-body-elegante); }
h1, h2, h3, h4, h5, h6 { font-family: var(--font-headings-elegante); }
*/
```

After:
```css
/* THEME 2: PROFESSIONAL ELEGANCE */

body { font-family: var(--font-body-elegante); }
h1, h2, h3, h4, h5, h6 { font-family: var(--font-headings-elegante); }
```
Click Apply, and you're done! Reload the book and enjoy!

🔧 Customization
Changing Themes (Manual)

You can switch themes at any time by following step 7 above. Remember to comment out the old theme before uncommenting the new one.

Adjusting Colors

All colors are defined as CSS variables at the beginning of the file, in the :root section. Feel free to modify the rgb() values to create your perfect palette.

```css
:root {
    /* Light Color Palette */
    --bg-light: rgb(245, 241, 233);
    --text-light: rgb(40, 40, 40);
    
    /* Dark Color Palette */
    --bg-dark: rgb(25, 25, 30);
    --text-dark: rgb(220, 215, 205);
}
```

🖥️ Recommended Font Size

These themes particularly shine with a slightly larger font size than the Calibre viewer's default.

A good starting point on a large monitor (like a 24") is between 20 and 22pt. You can adjust this in (I suggest changing it from Calibre itself and not from the code, within the open book, right-click, Font Size, and increase the amount there)

✍️ Credits

Design and Creation: Gemini 2.5 Pro
