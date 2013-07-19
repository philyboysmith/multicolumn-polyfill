## What is it?

This imitates the CSS3 multicolumn effect for list items for IE9 and IE8.
Use it with Modernizr.

## How does it work?
- Gets all children of an element
- Distributes them on new floating elements
- Hides the original
- Responsive behaviour: On resize, checks if column number changes

## Usage Example
```
 if (!Modernizr.csscolumns) {
   $('.mycolumn-element').multicolumn();
 }
```
