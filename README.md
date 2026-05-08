# ⚔ DungeonStylizer ⚔
The Dungeon Stylizer is a tool that transforms ordinary photos into retro game art (pixel art), capturing the gritty and nostalgic aesthetic of 1980s computer RPGs.

Here is how it works in simple terms:

Pixel Transformation: It reduces the resolution of your image so that it appears to be made of small blocks, eliminating the smoothness of modern photos.

Limited Palettes: Instead of millions of colors, the program forces the image to use only specific colors from classic palettes, such as "Dungeon Green," "Beholder Cyan," or "Blood Red".

Dithering Effect: To compensate for the limited colors, it uses dot patterns to create shadows and blends, a technique used by old computers that couldn't display smooth gradients.

Dungeon Outlines: It can identify the edges of objects in your photo and draw irregular, rustic outlines, making everything look hand-drawn on an ancient parchment or map.

Entirely in the Browser: The process is instantaneous and happens directly on your computer; you upload the image, adjust the sliders, and download the result immediately.

# ⚔ Dungeon Stylizer ⚔

Dungeon Stylizer is a specialized web tool designed to transform modern images into pixel art with the gritty, nostalgic aesthetic of 1980s computer RPGs. It combines real-time image processing with classic computer graphics techniques to create a rustic "old-school" look.

---

## ✨ Features

* **Dynamic Pixelation**: Reduce image resolution to achieve a classic blocky pixel look.
* **Thematic Color Palettes**: Apply iconic palettes including *Dungeon* (Green/Gold), *Beholder* (Cyan), *Ruins* (Sepia), *Necromancy* (Lime), and *Blood* (Red).
* **Dithering Algorithms**: Choose between methods like *Floyd-Steinberg*, *Atkinson*, and *Ordered Dithering* (4x4 or 8x8) to simulate color depth.
* **Intelligent Outlines**: Uses a Sobel edge detector to add irregular, hand-drawn style outlines reminiscent of ancient parchment sketches.
* **Full Artistic Control**: Adjust contrast, darkness, noise, saturation, and line thickness.
* **Interactive Preview**: Features a 4x zoom lens, a "Before & After" split-view slider, and a side-by-side grid view.

---

## 🛠 Tech Stack

The project is built using standard web technologies with no heavy external dependencies:

* **HTML5 & CSS3**: UI structure and styling with a retro terminal-inspired dark mode.
* **JavaScript (Vanilla)**: Core image processing logic and pixel manipulation via the **Canvas API**.
* **Google Fonts**: Uses the `VT323` bitmap font to reinforce the 8-bit aesthetic.

---

## 🚀 How to Use

1. **Load Image**: Open `dungeon_stylizer.html` in any modern browser and drag-and-drop your image into the ritual circle.
2. **Configure Style**: Adjust the sliders and select your desired palette and dithering method.
3. **Cast the Spell**: Click the **⚔ CONVERT ⚔** button to generate the artwork.
4. **Compare & Save**: Use the tabs to inspect the result and click **⬇ DOWNLOAD IMAGE ⬇** when finished.

---

## ⚖ License & Privacy

* **Privacy**: All processing is done locally on the client-side (your browser). No images are ever uploaded to a server.
* **Usage**: Perfect for RPG Game Masters creating monster illustrations, maps, or item cards with a vintage computer vibe.
