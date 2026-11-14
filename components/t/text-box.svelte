<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9y5vdabf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-box" {...props}></Icon>
<style>
:global(.o9y5vdabf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 5.5h13.75A2.625 2.625 0 0 1 21.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 15.875v-7.75A2.625 2.625 0 0 1 5.125 5.5M8 9.5h8m-4 0V15");
}

</style>
