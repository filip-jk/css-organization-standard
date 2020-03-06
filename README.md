# CSS Organization Standard

CSS Organization Standard is an opinionated CSS properties ordering.

## General Rules

1. Properties group separation (with an empty line) is not always required. We recommend separation when there are more than 4 properties.
2. Clockwise order: top, right, bottom, left.

## Basic Overview

```css
.class {
  /* Generated Content */
  content: ;
  
  /* Display, position & layout */
  display: ;
  position: ;
  z-index: ;
  top: ;
  right: ;
  bottom: ;
  left: ;
  flex: ; /* and other flex properties */
  float: ;
  clear: ;
  
  /* Visibility */
  visibility: ;
  opacity: ;
  
  /* Transform */
  transform: ;
  
  /* Transition & Animation */
  animation: ;
  transition: ;
  
  /* Box Model, from outside to inside */
  box-sizing: ;
  margin: ;
  box-shadow: ;
  outline: ;
  border: ;
  border-radius: ;
  padding: ;
  width: ;
  max-width: ;
  height: ;
  max-height: ;
  overflow: ;
  
  /* Background & Cursor */
  background: ;
  cursor: ;
  
  /* Content styling */
  color: ;
  font-family: ;
  font-size: ;
  line-height: ;
  font-weight: ;
  font-style: ;
  text-transform: ;
  word-spacing: ;
  list-style: ;
  vertical-align: ;
  
  /* Pseudo-classes & Pseudo-elements */
  :hover, :focus, :active, :before, :first-child, :last-child
  
}
```

## Full Overview

TO-DO

## Sources

1. https://9elements.com/css-rule-order/
2. https://github.com/brandon-rhodes/Concentric-CSS
3. https://github.com/necolas/idiomatic-css#declaration-order
