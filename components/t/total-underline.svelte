<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_h09rbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:total-underline" {...props}></Icon>
<style>
:global(.r_h09rbxi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4h10m-7 4h7M7 12h12M4 16.75h16m-16 3h16");
}

</style>
