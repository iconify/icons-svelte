<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3z7jhixr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tax-return-upload" {...props}></Icon>
<style>
:global(.l3z7jhixr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12.5h6.5L18 16v3.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2m4-10v7.25m-3.25-4L12 2.5l3.25 3.25");
}

</style>
