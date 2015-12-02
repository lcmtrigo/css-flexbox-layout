# CSS Flexbox Layout
## Building a Navigation Bar with Flexbox

### Resources
- [Flexbox - latest browser support](http://caniuse.com/#search=flexbox)

### Video review
- It's possible for an element to be both a flex item and a flex container.

Giving `.main-header` a `justify-content: space-between;` declaration positions the site name on the left side of the header and the navigation menu on the right:
```css
.main-header {
  justify-content: space-between; 
}
```