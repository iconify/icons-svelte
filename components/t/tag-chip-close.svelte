<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwvkqgbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tag-chip-close" {...props}></Icon>
<style>
:global(.hwvkqgbmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6.5h9A5.5 5.5 0 0 1 22 12a5.5 5.5 0 0 1-5.5 5.5h-9A5.5 5.5 0 0 1 2 12a5.5 5.5 0 0 1 5.5-5.5M6 12h5.5m3.5-1.75l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
