<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7mhwdrod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:websocket" {...props}></Icon>
<style>
:global(.j7mhwdrod) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3v18M21 3v18M7 8h10m-3-3l3 3l-3 3m3 5H7m3-3l-3 3l3 3");
}

</style>
