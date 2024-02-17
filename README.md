# Yu-Gi-Oh---Card-Flip-using-Bootstrap

Website output:
![image](https://github.com/iamzayd/Yu-Gi-Oh---Card-Flip-using-Bootstrap/assets/91972048/8b11fa69-11c9-448e-b64b-91b57c7ecfcd)

# Card Flip Effect with Bootstrap

## Experiment - 3

### Objective
The objective of this project is to implement a card-flip effect using Bootstrap. The goal is to create a responsive web page that displays a set of cards, each of which can be flipped to reveal additional content on the back side. This implementation utilizes Bootstrap for layout and styling to ensure compatibility across various devices and screen sizes.

### Tags Used
Let's delve deeper into the specific CSS tags and components used in the code:

#### Global Styles:
- `<body>` tag: Sets overall appearance for the entire page using:
  - `width: 90%`: Creates a centered content area with margins on both sides.
  - `margin: 0 auto`: Horizontally centers the content within the viewport.
  - `background-color`: Defines the page background color.
  - `font-size`: Sets the default font size for all text elements.

#### Bootstrap Integration:
- `<link>` tag: Imports the Bootstrap CSS framework, providing pre-defined styles.
- `<div>` with container class: Creates a responsive container element (inherited from Bootstrap).

#### Card Container:
- `.card-container` class: Styles the container holding all the cards:
  - `display: flex`: Arranges cards in a row using Bootstrap's flexbox functionality.
  - `justify-content: space-around`: Distributes cards evenly with space between them.

#### Individual Cards:
- `.card` class: Defines the overall structure and appearance of each card:
  - `width` and `height`: Set the dimensions of each card.
  - `perspective`: Creates a 3D perspective for the flip animation.
  - `margin`: Adds slight margins around each card.
  - `cursor: pointer`: Changes cursor to a hand on hover, indicating interactivity.

#### Flip Animation:
- `.card-inner` class: Responsible for the flip animation:
  - `width` and `height`: Ensures it fills the entire card area.
  - `transition`: Defines the smooth flipping animation on hover.
  - `transform-style`: Preserves the 3D context during the animation.
  - `transform: rotateY(-180deg);` (applied on hover): Rotates the back side 180 degrees to create the flip effect.

#### Card Sides:
- `.card-front` and `.card-back` classes: Represent the front and back sides of each card:
  - `position: absolute`: Positions them within the card container.
  - `backface-visibility: hidden`: Hides the back side when it's not facing forward.

#### Card Content:
- `.card-body` class: Styles the area holding text and image within each card:
  - `padding`: Adds space around the content for better readability.

#### Headings and Paragraphs:
- `h1`, `h3`, `h5`, `p` tags: Used for titles, subtitles, and descriptions:
  - Specific color styles are applied using CSS selectors for each heading level.

#### Images:
- `<img>` tags: Display the card images on both sides:
  - `src` attribute specifies the image source.
  - `alt` attribute provides alternative text for accessibility.

### Author
Najeeb Fariduddin Saiyed
