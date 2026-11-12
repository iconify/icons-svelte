<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwp5pobhv"/><path class="dj9zaictl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transfer-vertical-broken" {...props}></Icon>
<style>
:global(.dj9zaictl) {
  d: path("M4 14.5L10 20V10M10 4L10 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rwp5pobhv) {
  d: path("M20 9.5L14 4V14M14 20L14 17.5");
}

</style>
