<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymwrneb2m"/><path class="afp1lybxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:search-voice" {...props}></Icon>
<style>
:global(.afp1lybxq) {
  d: path("M2.5 10a6 6 0 0 0 12 0m-6 6v4.5m-2.5 0h5m3.75-4a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m4.75 2l1.75 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ymwrneb2m) {
  d: path("M8.5 2.5za3 3 0 0 1 3 3V10a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3");
}

</style>
