<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itrynstfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:search-plus" {...props}></Icon>
<style>
:global(.itrynstfh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m10.25 4.25l.75.75m3.5.5v6m-3-3h6");
}

</style>
