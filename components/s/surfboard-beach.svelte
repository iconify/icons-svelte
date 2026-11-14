<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf4hepfnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:surfboard-beach" {...props}></Icon>
<style>
:global(.nf4hepfnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21C5 14 8 6 12 3c4 3 7 11 4 18c-3.5 1-5 1-8 0m4-17.5v17");
}

</style>
