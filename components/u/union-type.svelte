<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rdrm-bcah"/><path class="zacln9bxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:union-type" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rdrm-bcah) {
  d: path("M6.875 2.5h2.25A4.375 4.375 0 0 1 13.5 6.875v2.25A4.375 4.375 0 0 1 9.125 13.5h-2.25A4.375 4.375 0 0 1 2.5 9.125v-2.25A4.375 4.375 0 0 1 6.875 2.5");
}

:global(.zacln9bxm) {
  d: path("M8.5 15a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

</style>
