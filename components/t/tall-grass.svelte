<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji532gbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tall-grass" {...props}></Icon>
<style>
:global(.ji532gbbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5h18m-14 0C7 14 5.5 8 3 3.5m9 18C12 14 12.5 8 14 3m3 18.5C17 15 18.5 10 21 6");
}

</style>
