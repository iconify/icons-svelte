<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gru5shbyw"/><path class="rc-lw2bxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:signal-2g" {...props}></Icon>
<style>
:global(.gru5shbyw) {
  fill: currentColor;
  d: path("M3 15.5h2.5v5H3ZM8.25 12h2.5v8.5h-2.5Z");
}

:global(.rc-lw2bxy) {
  d: path("M13.5 8H16v12.5h-2.5Zm5.25-4.5h2.5v17h-2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
