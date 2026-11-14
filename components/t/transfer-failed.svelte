<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3qjsgbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transfer-failed" {...props}></Icon>
<style>
:global(.b3qjsgbll) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h13m-3.5-3.5L17 6l-3.5 3.5M20 12H7m3.5-3.5L7 12l3.5 3.5m7.5-.75v3.5M18 21h.01");
}

</style>
