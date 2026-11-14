<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4d3b1b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rx-approved" {...props}></Icon>
<style>
:global(.k4d3b1b_a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.3 17.5H2.5v-14h17v9.8M6 7.5h10M6 11h10M6 14.5h5m3.75 3.5l2 2L21 15.75");
}

</style>
