<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am15vn2tz"/><path class="fj3h3ccrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snap-turn" {...props}></Icon>
<style>
:global(.am15vn2tz) {
  d: path("M5.5 20.5v-8A6.5 6.5 0 0 1 12 6h7");
}

:global(.fj3h3ccrv) {
  d: path("M15.5 2.5L19 6l-3.5 3.5m-8 1l-3-1.25m5.5-1.5L9 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
