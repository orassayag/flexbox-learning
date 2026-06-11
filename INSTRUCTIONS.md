# Instructions

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Initial Setup](#initial-setup)
3. [Install Dependencies](#install-dependencies)
4. [Running the Examples](#running-the-examples)
5. [Available Commands](#available-commands)
6. [Development Commands](#development-commands)
7. [Running Scripts](#running-scripts)
8. [Troubleshooting](#troubleshooting)
9. [Best Practices](#best-practices)
10. [Extending the Application](#extending-the-application)
11. [Documentation](#documentation)
12. [External Resources](#external-resources)
13. [Last Updated](#last-updated)
14. [Version](#version)

## Setup and Usage Instructions

## Prerequisites

### System Requirements

- A modern web browser (Chrome 29+, Firefox 28+, Safari 9+, Edge 12+)
- A code editor (VSCode recommended)
- Basic knowledge of HTML and CSS

### Knowledge Prerequisites

- Basic understanding of HTML tags and structure
- Familiarity with CSS selectors and properties
- Willingness to experiment and learn!

## Initial Setup

1. Clone the repository to your computer:

```bash
git clone https://github.com/orassayag/flexbox-learning.git
cd flexbox-learning
```

2. Open the project in your IDE (VSCode recommended)

**No build process or dependencies required** - this project uses pure HTML and CSS.

## Install Dependencies

There are no dependencies to install! This is a pure HTML/CSS project with no npm packages or build tools needed.

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
display: flex; /* Creates a flex container */
```

### Flex Property

```css
flex: 0 0 100px; /* flex-grow flex-shrink flex-basis */
```

- `flex-grow`: How much the item grows relative to others
- `flex-shrink`: How much the item shrinks relative to others
- `flex-basis`: The initial size before growing/shrinking

### Justify Content

```css
justify-content: space-between; /* Horizontal alignment */
```

### Flex Wrap

```css
flex-wrap: wrap; /* Allow items to wrap to new lines */
```

### Order

```css
order: 2; /* Change display order without changing HTML */
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

## Available Commands

Since this is a pure HTML/CSS project, there are no commands to run! Just open the HTML files in your browser.

### Development Commands

There are no development commands required! This project doesn't use any build tools or package managers.

### Running Scripts

There are no scripts to run! To view the examples:

1. Open any `.html` file directly in your browser
2. Or use VSCode's Live Server extension for auto-reload

## Troubleshooting

### Common Issues and Solutions

#### Browser Not Rendering Correctly

**Problem**: Layout looks broken in your browser
**Solutions**:

1. Make sure you're using a modern browser (Chrome 29+, Firefox 28+, Safari 9+, Edge 12+)
2. Check browser compatibility section for supported versions
3. Use browser dev tools to inspect elements and see what's wrong

#### Changes Not Reflecting

**Problem**: You modified CSS but don't see changes in browser
**Solutions**:

1. Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
2. Make sure you're editing the correct CSS file
3. If using Live Server, check that it's running and connected

#### Responsive Issues

**Problem**: Layout doesn't work on mobile/desktop
**Solutions**:

1. Check media query breakpoints in CSS
2. Use browser dev tools device mode to test responsive behavior
3. Verify you're using a mobile-first approach

## Best Practices

### Flexbox Best Practices

1. **Use `flex` shorthand**: Prefer `flex: 1 1 0` over individual properties for consistency
2. **Mobile-first design**: Start with mobile styles, then add media queries for larger screens
3. **Comment your code**: Explain what each flex property does for clarity
4. **Test responsiveness**: Resize your browser to ensure layouts work on all screen sizes
5. **Use semantic HTML**: Ensure your markup is accessible and meaningful

### Learning Best Practices

1. **Start simple**: Begin with `project2/index.html` to understand basics
2. **Make small changes**: Modify one property at a time to see its effect
3. **Inspect elements**: Use browser dev tools to experiment with flex properties live
4. **Read comments**: Examples include detailed explanations in comments
5. **Practice**: Try recreating layouts from scratch to reinforce learning

## Extending the Application

### Adding New Examples

1. Create a new HTML file (e.g., `my-example.html`)
2. Create a corresponding CSS file if needed
3. Link your CSS file in the HTML
4. Experiment with flex properties!
5. Consider adding comments to explain your code

### Organizing New Files

You can organize new examples in:

- `project1/` for advanced flexbox examples
- `project2/` for basic flexbox examples
- Or create a new directory for your own examples!

## Documentation

### Related Documentation

- [README.md](README.md) - Project overview and features
- [CONTRIBUTING.md](CONTRIBUTING.md) - How to contribute
- [CHANGELOG.md](CHANGELOG.md) - Version history
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) - Community guidelines

## External Resources

- [CSS-Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Interactive learning game
- [Flexbox Defense](http://www.flexboxdefense.com/) - Another interactive game
- [Can I Use: CSS Flexible Box Layout](https://caniuse.com/flexbox) - Browser compatibility info

## Author

- **Or Assayag** - _Initial work_ - [orassayag](https://github.com/orassayag)
- Or Assayag <orassayag@gmail.com>
- GitHub: https://github.com/orassayag
- StackOverflow: https://stackoverflow.com/users/4442606/or-assayag?tab=profile
- LinkedIn: https://linkedin.com/in/orassayag

## Last Updated

June 2026

## Version

1.0.0
