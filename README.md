# react-goban

*A stateless React component displaying a Goban.*

Its concern is the View: it implements neither Go rules nor game state.

![SVGoban demo](demo/demo.png)

## Usage

Install the package: `npm install react-goban --save`

Require it and use its `Goban` object:

```jsx
<Goban stones={{"P16":"black","Q4":"white","D4":"black","E16":"white"}} 
       onIntersectionClick={handler}
/>
```

### Goban Attributes
* `size` = a number between `9` and `19` (default)
* `theme` = `"classic"` (default) or `"paper"`
* `stones` = an object containing coordinates and colors as keys and values
* `onIntersectionClick` = callback function from (statefull) parent Component
* `nextToPlay` = color of hover effet on placeholders

## Demo

You may `make demo` and browse the bundled app at `demo\index.html`

## Roadmap

This is a Work In Progress.
* Add zoom
* Add markers (last stone played,...)

