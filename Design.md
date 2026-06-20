Subject: Create a Comprehensive "Design.md" File for an Open-Source Web Project

Role: Act as a Senior UI/UX Designer and Frontend Design System Engineer.

Context: 
I am building an open-source web application. I need you to generate a comprehensive, production-ready markdown file named `Design.md` that serves as the official Design System documentation for the project. The UI theme must perfectly replicate a style known as "Soft Neubrutalism" (also called Minimal Neubrutalism). It mimics the playful structure of traditional Neo-Brutalisme but swaps the harsh, aggressive elements for a softer, premium, and highly user-friendly modern aesthetic.

Core Design Pillars to Include and Specify:
1. "Rounded Cube" Concept: Absolute ban on harsh 90-degree sharp corners. Every primary component (buttons, cards, inputs) must use a smooth border-radius ranging from 12px to 16px.
2. The Extruded "Timbul" Effect: Buttons and active elements must look physically 3D and extruded. This must be achieved using a solid/hard shadow with 0px blur radius, paired with a distinct dark border.
3. Interactive "Depress" Animation: When elements are clicked/pressed (:active state), they must simulate a satisfying physical push-down effect by translating diagonally (e.g., translate 4px right and down) while reducing the box-shadow to 0px simultaneously.
4. Soft & Sophisticated Palette: Replace the blinding neon colors and thick pitch-black borders of classic brutalism with vibrant modern colors (such as deep Indigo/Purple), sophisticated slate/dark borders, and ultra-soft pastel gradient backgrounds.

Please structure the `Design.md` file exactly with the following sections:

---
# 1. Introduction & Design Philosophy
Explain the "Soft Neubrutalism" concept briefly. Focus on balancing bold structural layouts with soft, modern minimalism to create a clean, accessible, and high-converting user experience.

# 2. Design Tokens & Color Palette
Create a structured markdown table for the color tokens. Provide realistic premium HEX codes, naming conventions, and their precise roles:
- Primary Accent (e.g., Vibrant Indigo for CTA)
- Primary Border/Shadow (A slightly darker shade of the primary color)
- Secondary/Neutral Button Background (Pure White)
- Secondary Border/Shadow (Soft slate/gray)
- Text Primary (Deep dark slate)
- Text Muted/Secondary (Soft gray-blue for descriptions)
- Background Base & Soft Gradient (Ultra-light pastel/purple gradient tokens)

# 3. Typography Scale
Define a geometric sans-serif typography system (suggesting fonts like Plus Jakarta Sans or Inter). Specify font sizes (in rem or px), line-heights, and exact font-weights for:
- Hero Titles / H1 (Extra Bold/Black, high contrast)
- Section Headers / H2 (Bold)
- Body Text (Regular/Medium)

# 4. Component Specifications & Code Snippets
Provide clean, copy-pasteable code examples for both **Vanilla CSS** and **Tailwind CSS** for the following components:
- **Primary Extruded Button ("Timbul" Purple):** Must include the border, hard shadow, custom border-radius, and the interactive active state push-down animation.
- **Secondary Extruded Button ("Timbul" White):** A muted alternative with a gray/slate hard shadow.
- **Soft Neubrutalist Card:** A container for features or analysis data, featuring a clean white background, a very subtle border, and a soft ambient shadow to offset the hardness of the buttons.

# 5. Layout & Global Styles
Provide the global wrapper or body CSS class needed to achieve the soft background gradient layout seen in modern landing pages.

# 6. Developer Implementation Checklist
Write a practical markdown checklist for open-source contributors to ensure visual consistency across the codebase (e.g., cross-checking border-box properties, ensuring transition sync, font imports).
---

Tone of the Output Document: Professional, highly technical, clear, and inspiring for open-source developers. Ensure all code blocks are correctly formatted with syntax highlighting.
