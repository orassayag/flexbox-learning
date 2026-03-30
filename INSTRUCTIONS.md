# Instructions

## Setup Instructions

1. Clone the repository to your computer:
   ```bash
   git clone https://github.com/orassayag/flexbox-learning.git
   cd flexbox-learning
   ```

2. Open the project in your IDE (VSCode recommended)

**No build process or dependencies required** - this project uses pure HTML and CSS.

## Running the Examples

### Method 1: Using Live Server (Recommended)

If you use VSCode:
1. Install the "Live Server" extension by Ritwick Dey
2. Right-click on any `.html` file
3. Select "Open with Live Server"
4. The page will open in your browser with auto-reload on save

### Method 2: Direct File Opening

Simply open any `.html` file directly in your web browser:
- Double-click the file in your file explorer, or
- Right-click and select "Open with" → your preferred browser

## Project Structure

### Project 1 - Flexbox Examples
Located in `project1/` directory:

**Main Example** (`index.html`):
- Demonstrates flexbox item ordering with `order` property
- Shows how to reorder items without changing HTML structure

**Example 1** (`example-1/menu.html`):
- Basic responsive navigation menu
- Demonstrates `flex`, `justify-content`, and responsive behavior
- Mobile-first approach with media query at 768px

**Example 2** (`example-2/nested-menu.html`):
- Navigation with nested flexbox (social media icons)
- Shows how to combine multiple flexbox containers
- Demonstrates `flex: 1 1 0` pattern

**Example 3** (`example-3/grid-vs-stack.html`):
- Article grid layout with toggle functionality
- Switch between grid and stack layouts with jQuery
- Demonstrates `flex-wrap` and `flex-basis` with transitions

### Project 2 - Basic Flexbox Container
Located in `project2/` directory:

**Main Example** (`index.html`):
- Simple flexbox container with colored boxes
- Basic starting point for flexbox experiments
- No flexbox properties applied yet (ready for practice)

## Flexbox Concepts Covered

### Display Flex
```css
display: flex;  /* Creates a flex container */
```

### Flex Property
```css
flex: 0 0 100px;  /* flex-grow flex-shrink flex-basis */
```
- `flex-grow`: How much the item grows relative to others
- `flex-shrink`: How much the item shrinks relative to others
- `flex-basis`: The initial size before growing/shrinking

### Justify Content
```css
justify-content: space-between;  /* Horizontal alignment */
```

### Flex Wrap
```css
flex-wrap: wrap;  /* Allow items to wrap to new lines */
```

### Order
```css
order: 2;  /* Change display order without changing HTML */
```

## Browser Compatibility

All examples work in modern browsers:
- Chrome 29+
- Firefox 28+
- Safari 9+
- Edge 12+
- Opera 17+

For older browser support, consider using vendor prefixes.

## Learning Path

Recommended order to explore examples:

1. **Start with Project 2** (`project2/index.html`)
   - Understand the basic HTML structure
   - Experiment with adding flexbox properties in `style.css`

2. **Project 1 Main** (`project1/index.html`)
   - Learn about the `order` property
   - See how flex items can be reordered

3. **Example 1** (`project1/example-1/menu.html`)
   - Build a responsive navigation menu
   - Understand mobile-first responsive design

4. **Example 2** (`project1/example-2/nested-menu.html`)
   - Combine multiple flex containers
   - Create complex layouts with nested flexbox

5. **Example 3** (`project1/example-3/grid-vs-stack.html`)
   - Build dynamic layouts
   - Use flex-wrap for grid systems
   - Apply transitions to flex properties

## Experimenting

Feel free to modify any CSS file to experiment:
- Change `justify-content` values (flex-start, flex-end, center, space-around)
- Modify `flex` properties to see how items grow/shrink
- Add `align-items` for vertical alignment
- Try `flex-direction: column` for vertical layouts

## Responsive Design

Most examples use a mobile-first approach:
```css
@media screen and (min-width: 768px) {
    /* Desktop styles here */
}
```

Test responsive behavior by resizing your browser window or using browser DevTools device mode.

## Additional Resources

- [CSS-Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [MDN: Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Interactive game to learn flexbox

## Author

* **Or Assayag** - *Initial work* - [orassayag](https://github.com/orassayag)
* Or Assayag <orassayag@gmail.com>
* GitHub: https://github.com/orassayag
* StackOverflow: https://stackoverflow.com/users/4442606/or-assayag?tab=profile
* LinkedIn: https://linkedin.com/in/orassayag
