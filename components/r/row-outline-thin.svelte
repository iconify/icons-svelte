<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vyks9vbfn"/><path class="znap07bec"/><path class="wg1ykyaxv"/><path class="it83nbbll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:row-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.wg1ykyaxv) {
  d: path("M2 14.5h20");
}

:global(.znap07bec) {
  d: path("M2 9.5h20");
}

</style>
