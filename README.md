# Typography Ass-3 CSS

## Hosted Link: [View Project](https://saifulislam05.github.io/typography/)

## Project Structure
The project is structured with different content sections (`.box`) within a container (`.container`). Each section contains various typographic elements, including headings (`<h2>`), paragraphs (`p`), images (`img`), and an embedded YouTube video (`iframe`).


## HTML Structure
- `<h2>`: Represents a project title.
- `.container`: Wraps the content of the project.
- `.box`: Represents different content sections within the container.
- `p`: Represents paragraphs with textual content.
- `img`: Displays images within content sections.
- `iframe`: Embeds a YouTube video within the content.

## CSS Styles

### Global Styles
- `*`: Resets margin and padding for all elements to 0, ensuring consistent spacing.

### `.container` Selector:
- `display: flex;`: Uses flex layout for content alignment.
- `flex-direction: column;`: Stacks content vertically.
- `align-items: center;`: Centers content horizontally.
- `border-bottom: 3px solid rgba(0, 0, 0, 0.7);`: Adds a bottom border to the container with a specific color.

### `.box` Selector:
- `width: 30%;`: Sets the width of each box to 30% of the container.
- (Applied to multiple elements with class `.box`): Defines a consistent width for content sections.

### `p` Selector:
- `color: rgba(0, 0, 0, 0.6);`: Sets the text color for paragraphs.

