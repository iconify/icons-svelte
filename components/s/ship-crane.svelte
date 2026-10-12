<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="twh3olbvl"/><rect class="iubmw-bwy"/><path class="l6qa6acag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ship-crane" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iubmw-bwy) {
  width: 6.5px;
  height: 4.75px;
  x: 14.75px;
  y: 12.75px;
  rx: 0.75px;
}

:global(.l6qa6acag) {
  d: path("M17 14.25V16m2-1.75V16");
}

:global(.twh3olbvl) {
  d: path("M6.5 21.25v-17m-2.75 17h5.5m-6.5-17h18.5M6.5 8.5l4.25-4.25m7.25 0v8");
}

</style>
