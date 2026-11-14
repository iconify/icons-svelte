<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8be009se"/><path class="dv12iga-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:umbrella-open" {...props}></Icon>
<style>
:global(.dv12iga-f) {
  d: path("M12 11v7.5a2 2 0 0 1-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m8be009se) {
  d: path("M2.5 12a9.5 9.5 0 0 1 19 0q-3.25-2-6.25 0q-3.25-2-6.5 0q-3-2-6.25 0");
}

</style>
