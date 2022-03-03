## Update notes for version 0.1.0

Hey! DiceMaker v.0.1.0 brings some important and often-requested features, namely:

* Bumpers
* Custom image slots
* SVG support

### Bumpers

Bumpers can reduce warping of the printed dice. They are generally useful when placing supports or sanding printed masters.

Bumpers' generation is enabled by default. It can be turned off (per die) in the Attributes window.

![Image](/assets/img/update_notes_0_1_0_pic_01.png)

### Custom image slots

I've added five slots for custom Face Templates (named S1 to S5), and dice faces can now be reassigned to follow any Template. What it means in practice is that you can prepare an image for a high value, low value, etc., and assign it to any face of any die. Die face will follow any changes made to the Template.

![Image](/assets/img/update_notes_0_1_0_pic_02.png)

### SVG support

Perhaps most importantly, DiceMaker now supports SVG images for custom dice faces! Using SVGs over PNGs inherently results in higher quality engravings, because there's no fidelity loss during the vectorization process of raster images. This comes with a few caveats:

* All shapes in an SVG file are considered to be engravings - fill colors are disregarded
* Stroke widths are disregarded
* Non-closed shapes (single lines, polylines, etc.) aren't supported and *might* cause errors
* Adjacent shapes that share an edge but don't overlap **will** cause errors
* Self-intersecting shapes *might* cause errors, although there's a mechanism which should prevent that.

In other words: SVGs have to be properly prepared in order to work well. Here's a little guide:

![Image](/assets/img/update_notes_0_1_0_pic_03.png)

Happy making!