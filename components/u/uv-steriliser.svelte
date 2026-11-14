<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx4r0hbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:uv-steriliser" {...props}></Icon>
<style>
:global(.vx4r0hbbn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5h17v4h-17ZM4 16v4a1.5 1.5 0 0 0 1.5 1.5h13A1.5 1.5 0 0 0 20 20v-4M7 9.5l-1 3m6-3v3m5-3l1 3");
}

</style>
