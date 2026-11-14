<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k63gtmbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slip-dress" {...props}></Icon>
<style>
:global(.k63gtmbga) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.5q4.5 3 9 0L17 12l2.5 6.5l-15 3L7 12Zm0 0l1-5m8 5l-1-5");
}

</style>
