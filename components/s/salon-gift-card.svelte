<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_j3bxpvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:salon-gift-card" {...props}></Icon>
<style>
:global(.k_j3bxpvs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h19v13h-19Zm5.5 0C6.5 3 3 3 3.75 5.75C4.25 7.25 6 7.5 8 7.5Zm0 0C9.5 3 13 3 12.25 5.75C11.75 7.25 10 7.5 8 7.5Zm0 0V13m5 3.5h5");
}

</style>
