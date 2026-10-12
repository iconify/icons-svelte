<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq4garbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wardrobe-search-sharp" {...props}></Icon>
<style>
:global(.wq4garbnz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5V19.5H3.75zm8.25 0V19.5m-2.5-10V12m5-2.5V12m-8.25 7.5v1.75m11.5-1.75v1.75");
}

</style>
