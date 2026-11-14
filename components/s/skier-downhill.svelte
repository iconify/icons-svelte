<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="adgol0ftx"/><path class="w5vmnrbke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skier-downhill" {...props}></Icon>
<style>
:global(.adgol0ftx) {
  d: path("M13 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M13.5 8L10 12l3.5 3.5l-2 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5vmnrbke) {
  d: path("M13.25 9.25L17 11.5l2.5 5.75M3.5 16l17 4.75M2.5 8h4m-3 3h3");
}

</style>
