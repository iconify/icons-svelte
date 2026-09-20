<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxmcfjbnu"/><path class="bh4gsivfq"/><path class="u552kxblg"/><path class="pdpzifbii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:throw-error-outline-thin" {...props}></Icon>
<style>
:global(.bh4gsivfq) {
  d: path("m13 9 2.5 -2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pdpzifbii) {
  d: path("M17.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pxmcfjbnu) {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.u552kxblg) {
  d: path("M18.5 2.5V5");
}

</style>
