<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ow95k9elt"/><path class="ulne_dbqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vr-headset-sync" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ow95k9elt) {
  d: path("M9.5 9.5h5a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2M5.25 12H7.5m9 0h2.25");
}

:global(.ulne_dbqz) {
  d: path("M2.5 12a9.5 9.5 0 0 1 17.25-5.5m-3-.5l3 .5l.5-3M21.5 12a9.5 9.5 0 0 1-17.25 5.5m3 .5l-3-.5l-.5 3");
}

</style>
