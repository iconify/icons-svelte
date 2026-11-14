<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llu32mb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snowboard-halfpipe" {...props}></Icon>
<style>
:global(.llu32mb1t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8v4a8 8 0 0 0 16 0V8m-8.413-3.05l5.664-2.642a1.375 1.375 0 0 1 1.827.665a1.375 1.375 0 0 1-.665 1.827l-5.664 2.642a1.375 1.375 0 0 1-1.827-.665a1.375 1.375 0 0 1 .665-1.827");
}

</style>
