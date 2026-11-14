<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgfveg5si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:solid-state" {...props}></Icon>
<style>
:global(.bgfveg5si) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-14 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-14 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
