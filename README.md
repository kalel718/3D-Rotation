# 🖼️ 3D Image Carousel with HTML & CSS

A minimalist and elegant 3D image rotation gallery built with pure HTML and CSS. This project showcases the power of CSS `transform` properties to create dynamic and engaging visual effects without a single line of JavaScript.

### ✨ Features
- **Pure CSS Animation**: Smooth 360-degree rotation powered by `@keyframes`.
- **3D Transform Magic**: Uses `transform-style: preserve-3d` to create a true 3D space.
- **Dynamic Positioning**: Each image is positioned programmatically using CSS variables (`--i`) and `calc()` to ensure perfect spacing.
- **Image Reflection**: A cool reflective shadow is added for a polished look.

### 🚀 How It Works
The magic happens with CSS `transform` properties! A container `div` is set to `transform-style: preserve-3d` to act as a 3D space. Each image inside is rotated on the Y-axis and translated on the Z-axis, effectively creating a spinning cylinder of images. The `--i` variable on each `span` tag is used to calculate the exact rotation angle, ensuring each image is spaced at an equal distance.

### 🔧 Setup
1. Clone this repository: `git clone [repository-url]`
2. Navigate to the project folder.
3. Open `index.html` in your web browser to see the animation.
4. Replace the placeholder images in the `images` folder with your own!

### 💡 Live Demo





---
_Coded with passion by MK
