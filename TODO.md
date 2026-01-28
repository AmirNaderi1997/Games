# Mobile Touch Controls Implementation Plan

## Games to Update:
1. **Snake** - Add swipe gestures
2. **Retro Racer** - Add on-screen touch buttons
3. **Pong** - Add touch drag for paddle

## Implementation Details:

### Snake Touch Controls:
- Add `touchstart` and `touchend` event listeners
- Detect swipe direction (up, down, left, right)
- Prevent reverse direction movement
- Prevent page scrolling during swipe

### Retro Racer Touch Controls:
- Add CSS media query for mobile-only controls
- Create left/right touch buttons
- Semi-transparent styling
- Map touch to lane change logic

### Pong Touch Controls:
- Add touch event listeners on canvas
- Map vertical finger position to paddle Y
- Smooth tracking

## Files to Modify:
- index.html - Add CSS for mobile controls and JS for touch handling

## Testing Requirements:
- Desktop browser (keyboard still works)
- Mobile viewport (touch controls appear)
- Android browser
- iOS browser

