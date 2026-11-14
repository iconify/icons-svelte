<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkhmhdcsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:route-end" {...props}></Icon>
<style>
:global(.hkhmhdcsm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5h10a3 3 0 0 0 0-6H9a3.5 3.5 0 0 1 0-7h5m3 4V3m0 0l3.5 1.5L17 6Z");
}

</style>
