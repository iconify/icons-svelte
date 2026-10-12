<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x88mwabma"/><path class="t2zvjcbsg"/><path class="rhj7-w4rz"/><path class="tgipa-jqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stud-finder-sharp" {...props}></Icon>
<style>
:global(.rhj7-w4rz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

:global(.t2zvjcbsg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 13.25h6.5v2.5h-6.5Z");
}

:global(.tgipa-jqd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.17 6.67L12 3.837l2.83 2.833m-7.6-1.94a6.75 6.75 0 0 1 9.54 0");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x88mwabma) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10h13.5v11.25H5.25z");
}

</style>
