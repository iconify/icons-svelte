<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="m7ymxrukq"/><path class="c4vtm-bqw"/><path class="dw4-5zf2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:yin-yang-sharp" {...props}></Icon>
<style>
:global(.c4vtm-bqw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a9 9 0 0 1 0 18a5.5 5.5 0 0 1 0-9a5.5 5.5 0 0 0 0-9Z");
}

:global(.dw4-5zf2r) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7.5h.01m1.99 9h.01");
}

:global(.m7ymxrukq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a9 9 0 0 0 0 18");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
