<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtprusb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:soccer-cleats" {...props}></Icon>
<style>
:global(.mtprusb8i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 3.5l6.5 1l.5 5.5c5.5.5 11 2 11 6v1.5h-18Zm2.5 14v3m5.5-3v3m6.5-3v3");
}

</style>
