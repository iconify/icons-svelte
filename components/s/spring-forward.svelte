<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qm5ll9e7l"/><path class="xrfa8fz1m"/><path class="y1i9lh0ey"/><path class="n-5ydibjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spring-forward" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-5ydibjr) {
  d: path("m16 7l3 .75l-.25-3.25");
}

:global(.qm5ll9e7l) {
  d: path("M7 13.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.xrfa8fz1m) {
  d: path("M12 11v2.5h2");
}

:global(.y1i9lh0ey) {
  d: path("M5.75 19.75A9 9 0 0 1 19 7.75");
}

</style>
