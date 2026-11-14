<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uonwk1vkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snowboarder" {...props}></Icon>
<style>
:global(.uonwk1vkf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 9.75L11.5 14m-6-2.5l13-3m-11 11l4-5.5l4 3.5m-12 3l17-4.25");
}

</style>
