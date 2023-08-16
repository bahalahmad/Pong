# Basic Pong HTML and JavaScript Game

This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally and they're left as further exploration for the reader.

## Further Exploration

- Score
  - When a ball goes past a paddle, the other player should score a point. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.
 
  - ##Live link
  - Check out the [live demo](https://bahalahmad.github.io/Pong/) to see in action.
