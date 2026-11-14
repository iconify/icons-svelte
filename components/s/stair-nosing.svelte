<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izbhmoipm"/><path class="zgrlzwmil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stair-nosing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izbhmoipm) {
  d: path("M2.5 20.5H8V15h5.5V9.5H19V4h2.5");
}

:global(.zgrlzwmil) {
  d: path("M5.25 17.75v-5.5h5.5");
}

</style>
