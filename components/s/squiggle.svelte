<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzfom9b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:squiggle" {...props}></Icon>
<style>
:global(.hzfom9b3a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5C4.5 9.5 7 7 8.75 9S8 16 10 17.5s4-5.5 5.75-7.5S19.5 9 21 11.5");
}

</style>
