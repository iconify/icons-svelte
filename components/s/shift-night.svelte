<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huvz_0a8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shift-night" {...props}></Icon>
<style>
:global(.huvz_0a8p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 14.5A8.5 8.5 0 1 1 9.5 4A6.75 6.75 0 0 0 20 14.5m-2-9h.01M21 9h.01");
}

</style>
