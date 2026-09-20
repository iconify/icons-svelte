<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j93aodlin"/><path class="wehmxqbwf"/><path class="nex0q68jd"/><path class="es3-x2zcl"/><path class="i7-kopb4y"/><path class="vovviu-ly"/><path class="l2x-_sd5q"/><path class="zesf2kblt"/><path class="uxyzhxvwz"/><path class="f4wf9tbjy"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tree-of-thought-duotone-bold" {...props}></Icon>
<style>
:global(.es3-x2zcl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 14 5 5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f4wf9tbjy) {
  d: path("m7 14 5 5h5");
}

:global(.i7-kopb4y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j93aodlin) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l2x-_sd5q) {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nex0q68jd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t7ql4f28h) {
  d: path("m19 10 2 2 -2 2");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.vovviu-ly) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wehmxqbwf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 10 5 -5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zesf2kblt) {
  d: path("m7 10 5 -5h5");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
