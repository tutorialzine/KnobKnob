KnobKnob - a jQuery plugin for creating shiny knob controls
===========================================================

Usage:

```js
$('#elem').knobKnob({
		snap : 10,			// Snap to zero if less than this deg.
		value: 154,			// Default rotation
		turn : function(ratio){
			// Do what you want here. Ratio moves from 0 to 1
			// relative to the knob rotation. 0 - off, 1 - max
		}
	});
``` 

Head on to [Tutorialzine](http://tutorialzine.com/2011/11/pretty-switches-css3-jquery/) for a live demo.
