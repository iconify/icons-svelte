<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe8-x-brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:test-parallel" {...props}></Icon>
<style>
:global(.pe8-x-brs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h17.5M3 17h17.5m-3-13l3 3l-3 3m0 4l3 3l-3 3");
}

</style>
