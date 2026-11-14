<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1mn86b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:won-sign" {...props}></Icon>
<style>
:global(.h1mn86b1a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 4.5l4 15L12 6l5 13.5l4-15M3 11h18");
}

</style>
