# sharpInteractiveVisuals.min.js
Creates a `<canvas>` element for the interactive visuals. Current CSS for that was simply:
```css
canvas {
  display: block;
}
```

# p5.js library

p5.js is required. 
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.11.1/p5.js"></script>
```

# Optimization

## Desktop Experience
Runs real-time interactive visuals using 7 preloaded image assets to ensure smooth performance.

## Mobile Fallback
Automatically switches to a ```<video>``` element with a compressed, looped fallback video.
