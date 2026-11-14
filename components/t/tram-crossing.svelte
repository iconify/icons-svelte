<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5_9uab8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tram-crossing" {...props}></Icon>
<style>
:global(.a5_9uab8y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l5-10m12 10l-5-10M2.5 15h19m-19 4h19M8 2.5l8 6m0-6l-8 6");
}

</style>
