<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihtq93bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smart-pole" {...props}></Icon>
<style>
:global(.ihtq93bbc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11v10m-3.5 0h7M9.75 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M8 5a5.5 5.5 0 0 1 8 0");
}

</style>
