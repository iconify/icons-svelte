<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpdspyblc"/><path class="u-jpr9b_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:safe-vault" {...props}></Icon>
<style>
:global(.qpdspyblc) {
  d: path("M3 2.5h18v17H3Z");
}

:global(.u-jpr9b_s) {
  d: path("M6.5 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01m6.99-3v6m-11 5.5v2m11-2v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
