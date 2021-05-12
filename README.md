# tweakpane-plugin-cubic-bezier
Cubic bezier control for Tweakpane.


## Installation


### Browser
```html
<script src="tweakpane.min.js"></script>
<scirpt src="tweakpane-plugin-cubic-bezier.min.js"></script>
<script>
  const pane = new Tweakpane.Pane();
  pane.registerPlugin(TweakpaneCubicBezierPlugin);
</script>
```


### Package
```js
import {Pane} from 'tweakpane';
import * as CubicBezierPlugin from '@tweakpane/plugin-cubic-bezier';

const pane = new Pane();
pane.registerPlugin(CubicBezierPlugin);
```


## Usage
```js
pane.addBlade({
  view: 'cubicbezier',
  expanded: true,
  picker: 'inline',
  value: [0.5, 0, 0.5, 1],
});
```


[tweakpane]: https://github.com/cocopon/tweakpane/
