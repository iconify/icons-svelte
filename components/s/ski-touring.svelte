<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctims06ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-touring" {...props}></Icon>
<style>
:global(.ctims06ca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5V10a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v11.5ZM8.5 19l4-16M12 19l4-16");
}

</style>
