<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vy55o7bfi"/><path class="fwyf93qcw"/><path class="eur7p0b8m"/><path class="bu057zbzx"/><path class="eoov2wehu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stand-reminder-outline-thin" {...props}></Icon>
<style>
:global(.bu057zbzx) {
  d: path("M17 19V9");
}

:global(.eoov2wehu) {
  d: path("m14 12 3 -3 3 3");
}

:global(.eur7p0b8m) {
  d: path("m4 18 4 -4 4 4");
}

:global(.fwyf93qcw) {
  d: path("M8 8v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vy55o7bfi) {
  d: path("M5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
