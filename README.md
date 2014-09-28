Easing
------

**Bezier and easing functions based on Robert Penner's Easing Functions**

Example usage for function: ``Easing('easeOutQuart')``

For bezier curve use: ``Easing.bez('easeOutQuart')``

To convert a bezier curve to function use toFunction: ``Easing.toFunction([0.165, 0.84, 0.44, 1])``

Supported easing functions:

- linear
- ease
- easeIn
- easeOut
- easeInOut
- easeInQuad
- easeInCubic
- easeInQuart
- easeInQuint
- easeInSine
- easeInExpo
- easeInCirc
- easeInBack
- easeOutQuad
- easeOutCubic
- easeOutQuart
- easeOutQuint
- easeOutSine 
- easeOutExpo 
- easeOutCirc 
- easeOutBack 
- easeInOutQuad
- easeInOutCubic
- easeInOutQuart
- easeInOutQuint
- easeInOutSine
- easeInOutExpo
- easeInOutCirc
- easeInOutBack
- easeInElastic
- easeOutElastic
- easeInOutElastic
- easeInBounce
- easeOutBounce
- easeInOutBounce

Note that *elastic* and *bounce* are not available as bezier curves.
