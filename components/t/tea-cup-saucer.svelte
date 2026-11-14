<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvvuj4i_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tea-cup-saucer" {...props}></Icon>
<style>
:global(.kvvuj4i_n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9h12v4c0 2.5-2 4-6 4s-6-1.5-6-4Zm12 1c3.5 0 3.5 4.5 0 4.5m-13 6h14");
}

</style>
