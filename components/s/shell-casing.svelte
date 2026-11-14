<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_e3j_9hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shell-casing" {...props}></Icon>
<style>
:global(.h_e3j_9hk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 19V9.5L10.5 7V4.5q1.5-2.5 3 0V7L15 9.5V19Zm-1.5 0h9v2.5h-9Zm3-12h3");
}

</style>
