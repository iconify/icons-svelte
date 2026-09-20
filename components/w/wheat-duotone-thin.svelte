<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g69st4bxd"/><path class="nco06-bkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wheat-duotone-thin" {...props}></Icon>
<style>
:global(.g69st4bxd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nco06-bkq) {
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
}

</style>
