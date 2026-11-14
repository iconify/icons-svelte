<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzikzsbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stevenson-screen" {...props}></Icon>
<style>
:global(.hzikzsbxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h12v9H6ZM4.5 5L12 2.5L19.5 5ZM6 8h12M6 11h12M8 14v7.5m8-7.5v7.5");
}

</style>
