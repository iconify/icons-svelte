<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt757jeft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sports-shorts" {...props}></Icon>
<style>
:global(.qt757jeft) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.5h14L21 19h-7l-2-7.5l-2 7.5H3Zm-.5 3h15");
}

</style>
