# Style Guide

## Application Theme

The application follows a **light** theme, based on a modern, futuristic interface reminiscent of Jarvis from Iron Man. The user interface relies on cool blue and cyan accents, neutral backgrounds, and subtle surface elevations for a visually dynamic feel.

## Color Palette

- **Primary:** `#3b82f6` (bright blue)
- **Secondary:** `#64748b` (slate/gray)
- **Success/Accent:** `#06b6d4` (cyan)
- **Error:** `#EF4444` (red)
- **Background:** `#f9fafb` (off-white)
- **Surface:** `#ffffff` (pure white)
- **Text:** `#111827` (dark gray)
- **Gradient:** `from-3b82f6/10 to-gray-50`

### Sample CSS Variables

```css
:root {
  --primary: #3b82f6;
  --secondary: #64748b;
  --success: #06b6d4;
  --error: #EF4444;
  --background: #f9fafb;
  --surface: #ffffff;
  --text: #111827;
}
```

## Layout Description

- **Central quote panel** is the main focal point. Surrounded by animated graphics (SVG or CSS), floating edge panels, and glowing accent lines.
- **Buttons** are interactive and modern in style, placed directly below the quote panel.
- **Background** features smooth gradients and layered depths.

### Visual Elements

- Animated lines, dots, or "HUD"-style overlays accentuate the Jarvis-inspired look.
- Use subtle glows, shadows, and animated gradients to create a sense of energy and technology.
- Panels should float slightly above the background, with light drop-shadows.

## Font and Spacing

- Use modern, sans-serif fonts with clear readability.
- Prefer moderate border-radius and generous padding/margins to enhance approachability.
- Consistent spacing between floating panels and central content.

## Responsive Design

- The app layout adapts gracefully across desktop, tablet, and mobile viewports.
- Minimum touch targets for all controls.

## Accessibility

- Ensure enough color contrast for readability.
- Keyboard navigation and ARIA attributes where practical for interactive elements.

---

**Summary:** This guide ensures the app maintains a cohesive, light, and futuristic look and feel, closely aligned to Jarvis-style UI.

Task completed: Style guide documented.
