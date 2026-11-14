<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jh868ndmt"/><path class="ccqyc3e8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:x-mark" {...props}></Icon>
<style>
:global(.ccqyc3e8o) {
  d: path("M19.5 4.5q-6 6.5-15 15");
}

:global(.jh868ndmt) {
  d: path("M4.5 4.5q6 6.5 15 15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
