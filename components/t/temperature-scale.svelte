<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4ywy751r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:temperature-scale" {...props}></Icon>
<style>
:global(.a4ywy751r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19m-19 0v-8m4.75 8v-4m4.75 4v-8m4.75 8v-4m4.75 4v-8m-8.625 12.375za1.036 1.036 0 0 0 .851 1.625h.548a1.036 1.036 0 0 0 .851-1.625a1.368 1.368 0 0 0-2.25 0");
}

</style>
