# MONO

![Minimalist design system](https://mono.layogtima.com/images/screenshot.png)

## What is MONO?

MONO is a stripped-down design system that embraces the power of black, white, and the shades between. It's about removing color as a distraction to focus on what really matters: solid design fundamentals.

Think of it as design on hard mode-if it works in monochrome, it'll work anywhere.

> "Perfection is achieved not when there is nothing more to add, but when there is nothing left to take away." - Antoine de Saint-Exupéry

## Core Principles

### Reduction

Strip away the non-essential. Color, decoration, complexity-gone.

### Refinement

Perfect what remains: typography, spacing, and proportion.

### Rhythm

Create patterns and relationships with limited elements.

### Reaction

Test how users respond. Does it communicate? Does it connect?

## Key Components

- **Typography**: One font (Space Mono) expressing everything from whispers to shouts
- **Layout**: Grid systems that prove constraints breed creativity
- **Gallery**: Monochromatic marvels showing the system in action
- **Philosophy**: The thinking behind this deliberate limitation

## Quick Start

```bash
git clone https://github.com/layogtima/mono.git
cd mono
# Open any HTML file in your browser
```

### Basic Template

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MONO Project</title>

    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            fontFamily: {
              mono: ["Space Mono", "monospace"],
            },
          },
        },
      };
    </script>
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400;1,700&display=swap");
      * {
        font-family: "Space Mono", monospace;
      }
    </style>
  </head>
  <body class="bg-white text-black min-h-screen">
    <!-- Your design genius goes here -->
  </body>
</html>
```

## Design Elements

### Typography

Space Mono used in varying:

- Sizes (from microscopic to massive)
- Weights (light to bold)
- Spacing (tight to expansive)
- Styles (normal, italic, underlined)
- Effects (shadows, outlines, gradients)

### Layout

- Deliberate grid systems
- Asymmetrical compositions
- Rotated elements
- Pattern-based designs

### Visual Techniques

- Monochromatic palettes
- Strategic negative space
- Text as visual element
- Geometric compositions

## Examples Included

- `index.html` - Home page
- `typography.html` - Font explorations
- `layout.html` - Spatial compositions
- `gallery.html` - System in action
- `about.html` - Design philosophy

## MONO in the Wild

Check out these projects already embracing the monochromatic revolution:

### [layogtima.com](https://layogtima.com)

Amit's portfolio showcasing UI/UX design, hardware consulting, and flow artistry. Minimal and focused, just like its creator's attention span.

### [sm0.dev](https://www.sm0.dev/)

Shreshth's corner of the internet-web development, visualizations, and philosophical musings, all without the distraction of color.

### [seeds.layogtima.com](https://seeds.layogtima.com/)

A personal guide to growing food in Bengaluru. Proving that even plants, which literally exist to provide color in nature, can be documented in black and white.

### [india.xonotic.au](https://india.xonotic.au/)

A landing page for our small Xonotic community in India, focused on trying to get arena shooter games back in style! `You like Quake/Unreal Tournament? You're in for a treat :)`

## Contribute

Got MONOCHROME magic to share?

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/monochrome-magic`)
3. Commit your changes (`git commit -m 'Add my B&W brilliance'`)
4. Push to the branch (`git push origin feature/monochrome-magic`)
5. Open a Pull Request

## License

GPL v3. Share it, improve it, build with it.

## Credits

- Created by [Amit](https://layogtima.com)
- Inspired by minimalism and constraint-driven design
- Built with [Tailwind CSS](https://tailwindcss.com/)
