<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ix3wqdb5v"/><path class="wom5x5bys"/><path class="xda1ou47d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:summons-letter-sharp" {...props}></Icon>
<style>
:global(.ix3wqdb5v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.25h14.5v12.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wom5x5bys) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10L10 15l7.25-5m3.25-2.25v6");
}

:global(.xda1ou47d) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 17.25h.01");
}

</style>
