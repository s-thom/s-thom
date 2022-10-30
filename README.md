![Stuart Thomson](https://raw.githubusercontent.com/s-thom/s-thom/master/wave-banner.svg)

<details>
<summary>More info</summary>

## About me

I'm a guy that writes code. Whether anybody uses it or not doesn't really matter.

## This README

The SVG used at the top of this README is based on the version I use on my personal website. It's done in pure SVG using [SMIL](https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL), and barely scratches the surface of what's possible in SVG. This version uses quadratic bezier curves that animate their control points, leading to the appearance of the waves changing and overlapping. Quadratic curves are much easier to work with than cubics, as once the first control point is set, then all subsequent points have a single curve that passes through it. The curves themselves are generated with midpoint displacement, which finds the midpoint of a straight line, shifts it up/down, then draws two new lines. These points are ultimately what is used for each individual curve's start/end points.

- [Jost\* (Typeface)](https://indestructibletype.com/Jost.html)
- [CSS Tricks: A Guide to SVG Animations](https://css-tricks.com/guide-svg-animations-smil/)
- [SVG wave animation generator](https://loading.io/background/m-wave/) (the original inspiration for my own implementation)

And here's some other things that got me thinking about SVG in general, and may show up in later projects.

- [CSS Tricks: The Gooey Effect](https://css-tricks.com/gooey-effect/)
- [HTML + CSS in a GitHub README](https://github.com/cirosantilli/test-git-web-interface/blob/master/svg-foreignObject.svg) (I'm definitely using this later)

</details>
