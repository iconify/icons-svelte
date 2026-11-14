<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cczymubcm"/><path class="g-_hgowat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wifi-boost" {...props}></Icon>
<style>
:global(.cczymubcm) {
  d: path("M8.172 13.672a4 4 0 0 1 5.656 0m-8.485-2.829a8 8 0 0 1 11.314 0");
}

:global(.g-_hgowat) {
  d: path("M2.515 8.015a12 12 0 0 1 16.97 0M11 16.5h.01M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
