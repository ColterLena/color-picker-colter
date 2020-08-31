# Color Picker Colter
In this assignment, you'll create an HSL(a) color picker with React.

## Objectives

- Respond to user events in React
- Use state in react to drive changes to a user interface
- Use props to drive inline styles to dynamically update the appearance of DOM elements
- Understand RGB vs HSL color models
- Use controlled form inputs in React

## Requirements

Use `range` type `input` elements to drive a color display. You'll end up with something like this:

![](https://raw.githubusercontent.com/suncoast-devs/handbook/master/assignments/assets/color-picker.gif)

**HINT**: You will want to combine techniques of string interpolation and using
[inline styles in React](https://reactjs.org/docs/dom-elements.html#style), for
example:

```
const currentColor = `hsl(50,8%,20%)`
```

```
<div style={{ backgroundColor: currentColor }} >
  Hello World
</div>
```
- [ ] Represent the three values, `hue`, `saturation`, and `lightness` in your state.
- [ ] Add three sliders that update their respective values (`hue`, `saturation`, and `lightness`) in the state when changed.
- [ ] Display the color on the screen, in both text (i.e. `hsl(50, 8%, 20%)`) and the actual color as a background color on an element.
- [ ] Initialize the state to a random color when the page is loaded.
- [ ] Add a button that picks a new random color.
- [ ] In all cases, the sliders should be in the correct positions to represent the current color.
