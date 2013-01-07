retina-mixin
============

A less mixin for retina div images that will give styles for regular and 2x.

I took this from the retina.js solution and modified it a bit so you can use the .at2x() mixin for any div background, and include the parameters for

* x position
* y position
* repeat setting
* background attachment

If you don't pass any params, it just defaults to 0,0,no-repeat,scroll. It's a simple mixing but I find it useful often.
