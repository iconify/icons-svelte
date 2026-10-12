<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t9_psxdfo"/><path class="gv69jht3v"/><path class="sz0grsbiu"/><path class="gq2dgkb4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:train-alert-sharp" {...props}></Icon>
<style>
:global(.gq2dgkb4a) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 17.25l-2.25 4m8.75-4l2.25 4");
}

:global(.gv69jht3v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5.5h8.5V10h-8.5z");
}

:global(.sz0grsbiu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 13.75h.01m6.49 0h.01");
}

:global(.t9_psxdfo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v14.5H5.25z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
