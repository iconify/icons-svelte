<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja5un3p0l"/><circle class="fs6wrlbbp"/><path class="srx2ybb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spending-limit" {...props}></Icon>
<style>
:global(.fs6wrlbbp) {
  cx: 12px;
  cy: 14.75px;
  r: 6px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja5un3p0l) {
  d: path("M3 11V5.75h18V11");
}

:global(.srx2ybb7d) {
  d: path("M13.81 13.29c-.25-.62-.93-1.08-1.71-1.08c-.99 0-1.71.56-1.71 1.33c0 1.77 3.56.99 3.56 2.88c0 .81-.78 1.36-1.86 1.36c-.84 0-1.55-.46-1.86-1.08");
}

</style>
