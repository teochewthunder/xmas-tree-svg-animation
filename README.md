# Xmas Tree SVG Animation

This SVG animation is made out of a few parts. The *svgContainer* div moves the SVG middle of the screen.

## Tree
- path tag's nodes are relatively defined so that maintenance later on will be less of a hassle.
- Bezier Curves are included in the path.

## Star
- circle tag situated at the starting point of the tree path, which is at the top.
- animation tag within the circle tag to change the radius, repeats infinite times.

## Ball decorations
- several circle tags, all at random locations within the tree, and random sizes.
- animation tag within each circle tag, with animation times randomly defined.
- radialGradient tag for each circle's fill.

## Text
- text tags, pixel-adjusted position.

***Note:** Animations do not work in Internet Explorer.*
