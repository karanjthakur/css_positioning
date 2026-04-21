# CSS Positioning Demo

Web Link : https://karanjthakur.github.io/css_positioning/

This project is a simple interactive demo that shows how different CSS `position` values affect element layout.

## What This Demo Covers

- Static positioning
- Relative positioning
- Absolute positioning
- Fixed positioning

The page includes buttons to switch between examples. Each example displays the CSS snippet used and a box showing the visual behavior.

## Project Structure

- `index.html`: Page structure, demo sections, and button click logic
- `style.css`: Visual styles and positioning rules for each demo box
- `README.md`: Project documentation

## How To Run

1. Open the project folder.
2. Open `index.html` in any modern browser.

No build tools, package manager, or server setup is required.

## How It Works

- Buttons at the top toggle visibility of one demo section at a time.
- The script in `index.html` sets `display: block` for the selected section and `display: none` for others.
- Each section applies one positioning rule to its `.box` element:
	- `position: static`
	- `position: relative`
	- `position: absolute`
	- `position: fixed`

## Learning Notes

- `static` is the default; `top` and `left` have no effect.
- `relative` keeps the element in normal flow, then offsets it.
- `absolute` removes the element from normal flow and positions it relative to the nearest positioned ancestor (or viewport if none).
- `fixed` positions the element relative to the viewport and it stays in place while scrolling.

## Browser Support

Works in all modern browsers that support standard HTML, CSS, and JavaScript.
