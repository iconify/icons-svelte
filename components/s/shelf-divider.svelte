<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9na_igxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shelf-divider" {...props}></Icon>
<style>
:global(.x9na_igxf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5v19m0-11h19V13h-19Zm0 7.5l5-5m-3-8.5H10v6H4.5Zm10.5 1h5.5v5H15Zm-2.5-3v8");
}

</style>
