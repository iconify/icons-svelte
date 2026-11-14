<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf6dikvgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:speed-table" {...props}></Icon>
<style>
:global(.gf6dikvgx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 16h20M2.5 16l5-6.5h9l5 6.5m-11-3.75V16m3-3.75V16");
}

</style>
