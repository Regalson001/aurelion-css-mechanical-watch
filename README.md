
# AURELION — Pure CSS Mechanical Watch

A premium mechanical watch and analog clock showcase built with HTML5 and CSS3. Features animated clock hands, a skeleton-inspired gear assembly, metallic finishes, and a detailed luxury timepiece interface.

## Overview

AURELION explores the visual engineering of mechanical horology through CSS. The project combines precision positioning, animated transformations, layered gradients, and responsive design to create a modern luxury watch experience.

## Features

- Animated hour, minute, and second hands
- CSS keyframe-based timekeeping animation
- 12 Roman numeral hour indicators
- 60 calculated minute markers
- Skeleton-inspired mechanical gear assembly
- Alternating gear rotation animations
- Brushed metallic dial
- Titanium-inspired outer case
- Champagne-gold and copper details
- Sapphire-inspired glass reflections
- Layered case bevels and shadows
- Responsive watch layout
- Reduced-motion accessibility support

## Technologies

- HTML5
- CSS3
- CSS Custom Properties
- CSS Keyframes
- CSS Transforms
- CSS Gradients
- CSS Grid
- Flexbox
- Responsive Media Queries

## Project Structure

```text
aurelion-css-mechanical-watch/
├── index.html
├── styles.css
├── README.md
├── LICENSE
└── .gitignore
```

## Getting Started

1. Clone this repository.
2. Open the folder in Visual Studio Code.
3. Open `index.html` in your browser.
4. No JavaScript, package installation, or build process is required.

## Animation Engineering

The three hands use independent CSS animations:

| Hand | Duration | Timing |
|---|---:|---|
| Second | 60 seconds | `steps(60, end)` |
| Minute | 3600 seconds | `linear` |
| Hour | 43200 seconds | `linear` |

The hands rotate around their base pivots using `transform-origin`.

## Core CSS Concepts

### Transform Origin

The hands are positioned at the center of the dial and rotate around their bottom edge.

```css
.hand {
  transform-origin: 50% 100%;
}
```

### Custom Properties

CSS variables control dimensions, metallic colors, and animation durations.

### Conic Gradients

Used to create the brushed dial texture, metallic case, and gear details.

### Radial Gradients

Used to create depth in the dial, gear hubs, and central pivot.

### Calculated Positioning

Hour and minute markers are positioned around the circular dial using CSS transforms and custom properties.

## Important Note

AURELION is a visual CSS timepiece, not a functional precision clock. Its hands run on independent animation cycles and do not synchronize to the current system time. The gear assembly is an illustrative visual mechanism rather than a physically calibrated gear train.

## Future Improvements

- Real-time clock synchronization
- Interactive watch crown
- Adjustable time controls
- Additional dial colorways
- More detailed gear components
- Watch strap customization
- Interactive movement inspection
- Additional case materials

## Author

**Stephen Oyugi**

Front-End Developer | AI Automation & Machine Learning Enthusiast

- GitHub: https://github.com/Regalson001
- LinkedIn: https://linkedin.com/in/stephenoyugi001

## License

This project is licensed under the MIT License.
