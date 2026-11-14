<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uydtsg4pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sledgehammer" {...props}></Icon>
<style>
:global(.uydtsg4pq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M1.04 9.525L9.525 1.04l4.243 4.242l-8.486 8.486Zm7.424 1.061l2.122-2.122l9.192 9.193l-2.121 2.121Z");
}

</style>
