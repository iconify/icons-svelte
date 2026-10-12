<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqfpa7bwx"/><path class="t2g-sibgb"/><path class="rgf3glbhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:webhook" {...props}></Icon>
<style>
:global(.fqfpa7bwx) {
  d: path("M17.4 16.48h-5.39c-.99 0-1.76.85-2.23 1.71A3.6 3.6 0 0 1 3 16.5c.01-.63.18-1.26.51-1.8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rgf3glbhv) {
  d: path("m12 6.6l2.82 5.16c.47.87 1.59 1.14 2.58 1.14a3.6 3.6 0 0 1 0 7.2");
}

:global(.t2g-sibgb) {
  d: path("m6.6 16.5l2.82-5.2c.48-.87.09-1.96-.45-2.79a3.6 3.6 0 1 1 6.2-3.66");
}

</style>
