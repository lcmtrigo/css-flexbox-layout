# CSS Flexbox Layout
## Vertical and Horizontal Centering
### Video review

#### Three ways to center-align elements using flexbox

Set the flex container's `justify-content` and `align-items` values to `center`:
```css
.container {
  justify-content: center;
  align-items: center;
}
```

Set the flex container's `justify-content` value to `center`, while setting the flex item's `align-self` value to `center`:
```css
.container {
  justify-content: center;
}
.item {
  align-self: center;
}
```

Set the flex item's `margin` value to `auto`:
```css
.item {
  margin: auto;
}
```