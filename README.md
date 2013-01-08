# retina-mixin
============
I took this from the retina.js solution and modified it a bit. All credit goes to https://github.com/imulus/retinajs, I just tweaked this for my needs. This mixin includes most of the parameters you need, so you don't need to call them out twice. It can all be done in the mixin. 

A less mixin for retina div images that will give styles for regular and 2x. You can use this for any background you need since it outputs the regular css and the @media query styles for retina.

You still must include params for:
* path
* effective size

You can then include the parameters for:
* x position
* y position
* repeat setting
* background attachment

If you don't pass any optional params, it just defaults to "0, 0, no-repeat, scroll". It's a simple mixin but I find it useful often.
