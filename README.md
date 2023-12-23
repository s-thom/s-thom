![Stuart Thomson](https://raw.githubusercontent.com/s-thom/s-thom/master/wave-banner.svg)

<details>
<summary>More info</summary>

## About me

I'm a guy that writes code. Whether anybody uses it or not doesn't really matter.

## This README

The SVG used at the top of this README is based on the version I use on my [personal website](https://sthom.kiwi). It's done in pure SVG using [SMIL](https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL) to control the animation. Each "wave" has a list of variations that it cycles between, and each one's animation cycle is offset slightly so they aren't all stopping/starting at the same time. Waves themselves are generated using a variation on the midpoint displacement algorithm, where new control points are added ahlfway between existing ones. Each iteration of the algorithm also reduces how much each control point contributes to the overall height.

- [CSS Tricks: A Guide to SVG Animations](https://css-tricks.com/guide-svg-animations-smil/)
- [SVG wave animation generator](https://loading.io/background/m-wave/) (the original inspiration for my own implementation)
- Font: [Jost*](https://indestructibletype.com/Jost.html)

</details>
