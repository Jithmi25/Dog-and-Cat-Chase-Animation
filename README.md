# Dog and Cat Chase Animation

This project is an HTML and CSS animation showcasing a playful scene where a dog is running after a cat, and a girl is running after the dog. The animation is achieved using CSS keyframes to simulate running movements.

## Project Features
- **Animation Sequence**: The dog chases the cat, followed by a girl running after the dog.
- **CSS Keyframes**: Smooth running motion for each character.
- **Responsive Design**: The animation adjusts for different screen sizes.

## Technologies Used
- **HTML**: Structure of the animation characters and elements.
- **CSS**: Keyframes and styling for animations.

## How It Works
1. **Characters**: The dog, cat, and girl are represented with HTML elements, styled and animated using CSS.
2. **Keyframes**: Each character has a unique keyframe animation to create a running motion.
3. **Looping Animation**: The animation is set to loop to keep the characters in a continuous chase sequence.

## Usage
1. Clone this repository to your local machine.
2. Open `index.html` in a web browser to view the animation.

## Code Snippet
Here's a preview of the CSS keyframes used to animate the running motion:

```css
@keyframes runDog {
    0% { transform: translateX(0); }
    100% { transform: translateX(100%); }
}

@keyframes runCat {
    0% { transform: translateX(0); }
    100% { transform: translateX(80%); }
}

@keyframes runGirl {
    0% { transform: translateX(0); }
    100% { transform: translateX(60%); }
}
