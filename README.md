# CSS Flexbox Layout
## Creating a Sticky Footer with Flexbox

A sticky footer is a footer that sticks to the bottom of the page, regardless of the amount of content on the page. If a page’s content is shorter than the height of the browser, you end up with a footer that sits near the middle of the page, instead of at the bottom. Flexbox is a great solution for fixing these types of problems.

###Video review

- When you make body a flex container, it lays out all its direct children horizontally on a single line.
- Setting the flex-direction of body to column stacks its flex items vertically.
- 1vh is equal to 1/100th or 1% of the viewport height.

###Sticky footer snippet
```css
body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.row {
  flex: 1;
}
```