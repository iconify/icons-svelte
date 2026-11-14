<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z35agkb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:where-filter" {...props}></Icon>
<style>
:global(.z35agkb0n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12h12.5m-19 0l2 2l3-4M9 5h2m2.75 0h2m2.75 0h3M9 19h2m2.75 0h2m2.75 0h3");
}

</style>
