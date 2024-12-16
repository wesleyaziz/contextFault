# No Signal Effect

An interactive web effect that simulates TV signal interference. When users click on the text, it creates a visual effect similar to TV signal distortion.

## Preview Effect

- Static text displays "NO SIGNAL"
- Glitch effect triggered on click
- Red and blue color shift effect 
- Random position shifts and clip animations

## Technical Implementation

### HTML
- Multiple paragraph elements to create overlapping text effects
- Click event binding to trigger glitch effect

### CSS/SASS
- Flexbox for centering layout
- Mix-blend-mode for color blending
- Transform for text displacement
- Clip-path for text clipping

### JavaScript
- setInterval for animation loop
- Random number generation for displacement and clip areas
- Class toggling for effect control

## How to Use

1. Download project files locally
2. Open index.html
3. Click on text to trigger glitch effect

## File Structure
```
no-signal-effect/
│
├── index.html
├── style.css
├── style.sass
└── README.md
```

## Customization

The following parameters can be adjusted in style.sass:
- Font size
- Text color
- Displacement effect range
- Animation duration

## Features

- Responsive design
- Smooth animations
- Cross-browser compatible
- Lightweight implementation

## Dependencies

- No external libraries required
- Pure HTML, CSS/SASS and JavaScript

## License

MIT License
