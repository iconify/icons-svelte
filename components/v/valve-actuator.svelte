<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jidmyhb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:valve-actuator" {...props}></Icon>
<style>
:global(.jidmyhb4b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 11.5l8.5 4.25l8.5-4.25V20L12 15.75L3.5 20ZM12 9v6.75M7.5 3h9v6h-9Z");
}

</style>
