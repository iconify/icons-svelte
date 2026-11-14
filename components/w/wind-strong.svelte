<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khut7im_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wind-strong" {...props}></Icon>
<style>
:global(.khut7im_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5H14a2.75 2.75 0 1 0-2.75-2.75M2.5 12h19m-19 4.5H16a2.75 2.75 0 1 1-2.75 2.75");
}

</style>
