<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="l9kl1cbdj"/><path class="aufabbv2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shareholder" {...props}></Icon>
<style>
:global(.aufabbv2i) {
  d: path("M3.5 21.25h9a.75.75 0 0 0 .75-.75c0-3.62-2.42-6.25-5.25-6.25s-5.25 2.63-5.25 6.25a.75.75 0 0 0 .75.75M14 10.5l3-3l2 2L21.25 7M18.5 5.25h2.75V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l9kl1cbdj) {
  cx: 8px;
  cy: 9px;
  r: 3px;
}

</style>
