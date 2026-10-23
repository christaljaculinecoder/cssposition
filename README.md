
# CSS Positioning Practice

## Objective

**Practice CSS positioning properties and understand how different elements are positioned on a webpage using HTML and CSS.**

## Task Description

Create a webpage containing four boxes with different background colors and apply CSS styling to practice box sizing, dimensions, margins, borders, and positioning properties.

## Technologies Used

- HTML5
- CSS3

## HTML Structure

- A container element that holds Box1, Box2, and Box3.
- Box4 is placed outside the container.
- An external CSS file named `style.css` is linked to the HTML document.

## CSS Concepts Practiced

### 1. Universal Selector and Box Sizing

- `*` selector applies `box-sizing: border-box` to all elements.
- `border-box` includes padding and borders within the specified width and height.

### 2. Body Height

- `height: 2000px` gives the body a fixed height to create a vertically scrollable page.

### 3. Container Styling

- Width: `500px`
- Height: `500px`
- Border: `2px solid black`
- Left margin: `100px`
- Top margin: `100px`

### 4. Box Styling

- Width: `100px`
- Height: `100px`
- Border: `2px solid black`
- Text color: White

### 5. Background Colors

- **Box1:** Red
- **Box2:** Green
- **Box3:** Violet
- **Box4:** Linear gradient from green to yellow

## CSS Positioning Properties

### Box1 — Default Positioning

Box1 uses the default positioning behavior, `position: static`, because no positioning property is specified.

### Box2 — Relative Positioning

- `position: relative`
- `right: 0px`
- `top: 0px`

Relative positioning allows an element to be positioned relative to its normal position. With both offsets set to `0px`, Box2 remains in its normal position.

### Box3 — Fixed Positioning

- `position: fixed`

Fixed positioning removes the element from the normal document flow and positions it relative to the viewport by default. The box remains in the same viewport position while scrolling. Since no `top`, `right`, `bottom`, or `left` offset is specified, its exact position depends on the browser's layout behavior.

### Box4 — Sticky Positioning

- `position: sticky`
- `top: 100px`

Sticky positioning allows Box4 to behave like a normally positioned element until it reaches the specified offset of `100px` from the top of the viewport while scrolling, subject to its scrolling container and layout constraints.

## Project Structure

```text
CSS-Positioning-Practice/
├── index.html
└── style.css
```

## Learning Outcomes

- Understand the relationship between HTML structure and CSS styling.
- Apply the universal selector.
- Understand the `box-sizing` property.
- Set element dimensions, borders, and margins.
- Apply background colors and linear gradients.
- Practice `static`, `relative`, `fixed`, and `sticky` positioning.
- Observe how positioned elements behave while scrolling.

## Conclusion

This practice project demonstrates the use of HTML and CSS to create and style boxes while exploring different CSS positioning properties and their behavior on a webpage.

````
