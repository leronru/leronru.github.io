🖼️ Image to ASCII Converter

Transform Images Into Text-Based Art.

<p align="center">
  <strong>Görsellerinizi ASCII karakterleriyle yeniden oluşturun.</strong>
</p><p align="center">
  A modern, lightweight and browser-based image-to-ASCII conversion tool.
</p><p align="center">
  <a href="https://leronru.github.io/ascii-art">
    <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-00C853?style=for-the-badge" alt="Live Demo">
  </a>
</p><p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Canvas_API-00C853?style=for-the-badge">
</p>---

🌐 Live Demo

Try it directly in your browser. No installation required.

🔗 "https://leronru.github.io/ascii-art" (https://leronru.github.io/ascii-art)

Upload an image, customize the conversion settings and transform your pictures into ASCII artwork within seconds.

📌 About The Project

Image to ASCII Converter is a web-based creative tool that transforms ordinary digital images into character-based visual artwork.

The application analyzes individual image pixels, calculates their brightness values and maps them to different ASCII characters to reconstruct the original image using text.

From classic terminal aesthetics to detailed character-based portraits, the converter offers an accessible way to explore the intersection of image processing, programming and digital art.

«Every pixel has a character. Every character creates art.»

✨ Features

🖼️ Image Import

- Upload images directly from your device.
- Drag-and-drop image support.
- Import images through direct URLs.
- Supports common image formats including JPG, PNG, GIF and WebP.

⚙️ Advanced Conversion Controls

- Adjustable output width (20–200 characters).
- Adjustable font size.
- Brightness adjustment.
- Contrast adjustment.
- Inverted brightness mapping.
- Automatic image-to-character conversion.

🎨 Character Customization

Choose between five different character sets:

Mode| Description
Standard| Balanced ASCII rendering
Detailed| Extended character mapping
Simple| Minimal character selection
Blocks| Block-based visual rendering
Inverted| Reverse brightness mapping

🌈 Color Customization

Choose your preferred output color:

- 🟢 Green
- 🔴 Red
- 🔵 Cyan
- 🟡 Yellow
- 🟣 Magenta
- ⚪ White

🚀 Quick Presets

Get started faster with predefined configurations:

- Low Quality
- Medium Quality
- High Quality
- Retro

📤 Export & Sharing

Save and reuse your generated artwork:

- Copy ASCII output to clipboard.
- Download as TXT.
- Export as standalone HTML.
- Export as PNG image.

🔬 How Does It Work?

The converter uses JavaScript and the HTML5 Canvas API to analyze image pixels and reconstruct them using text characters.

Conversion Pipeline

       INPUT IMAGE
            |
            v
       IMAGE LOADING
            |
            v
       HTML5 CANVAS
            |
            v
       PIXEL ANALYSIS
            |
            v
     RGB BRIGHTNESS
       CALCULATION
            |
            v
      CHARACTER MAPPING
            |
            v
       ASCII RENDERING
            |
            v
        FINAL ART

Pixel Brightness Calculation

The application calculates pixel brightness using a weighted RGB formula:

[
L = 0.299R + 0.587G + 0.114B
]

Where:

- "R" = Red channel
- "G" = Green channel
- "B" = Blue channel
- "L" = Pixel brightness

The calculated brightness determines which character is selected from the active character set.

Character Mapping Example

const charIndex = Math.floor(
    adjustedBrightness / 255 *
    (selectedCharSet.length - 1)
);

row += selectedCharSet[charIndex];

This process is repeated across the image to generate the final ASCII representation.

🛠️ Technology Stack

Technology| Purpose
HTML5| Application structure
CSS3| Interface and responsive styling
JavaScript| Application logic and conversion engine
Canvas API| Pixel analysis and image processing
FileReader API| Local image loading
Blob API| File generation and exporting
Clipboard API| Copying generated artwork

🔒 Privacy & Processing

The application is designed around client-side image processing.

- No account registration is required.
- No backend installation is required.
- Local images are processed directly in the browser.
- Local image files are not uploaded to a project server for conversion.
- External image URLs may be subject to CORS restrictions.

🎯 Use Cases

Image to ASCII Converter can be used for:

- Digital art and creative typography.
- Terminal and command-line aesthetics.
- Retro computer graphics.
- Social media artwork.
- Programming experiments.
- Learning pixel manipulation and image processing.
- Creative coding projects.

🗺️ Future Development

Potential improvements and planned features:

- [ ] Real-time video-to-ASCII conversion.
- [ ] Animated GIF frame-by-frame conversion.
- [ ] Full RGB colored ASCII rendering.
- [ ] Custom character set editor.
- [ ] Batch image processing.
- [ ] Advanced image preprocessing.
- [ ] Adjustable aspect ratio.
- [ ] Web Worker-based processing.
- [ ] Additional export formats.
- [ ] Enhanced mobile experience.


---

<p align="center">
  <strong>IMAGE → ASCII</strong>
  <br>
  Transforming Pixels Into Characters.
  <br><br>
  Made with JavaScript, HTML5 Canvas and Creativity.
  <br><br>
  <a href="https://leronru.github.io/ascii-art">🚀 Explore the Live Application</a>
</p>
