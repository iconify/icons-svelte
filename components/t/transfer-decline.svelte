<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5k-1xb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transfer-decline" {...props}></Icon>
<style>
:global(.n5k-1xb2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h13m-3.5-3.5L17 6l-3.5 3.5M20 12H7m3.5-3.5L7 12l3.5 3.5m5 0l5 5m0-5l-5 5");
}

</style>
