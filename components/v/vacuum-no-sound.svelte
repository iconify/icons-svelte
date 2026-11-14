<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcvlqjd1c"/><path class="hja1_qbxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vacuum-no-sound" {...props}></Icon>
<style>
:global(.hcvlqjd1c) {
  d: path("M4 21.5V10a8 8 0 0 1 16 0v11.5m-17.5 0h19");
}

:global(.hja1_qbxg) {
  d: path("M9 16v-3.5a3 3 0 0 1 6 0V16m-7.5 0h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
