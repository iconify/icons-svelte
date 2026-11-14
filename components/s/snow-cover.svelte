<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eijdnga2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snow-cover" {...props}></Icon>
<style>
:global(.eijdnga2y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5v-2C3 9 6 7 9 7.5c2 .25 3 1 4.5 1c2.5 0 4-1.5 6-.5c1.5.75 1.5 2.5 1.5 3.5v2m-18.5 0h19M6 17.5h12");
}

</style>
