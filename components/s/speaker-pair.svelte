<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfhnicc7r"/><path class="yw7nsuu5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:speaker-pair" {...props}></Icon>
<style>
:global(.bfhnicc7r) {
  d: path("M2.5 4h8v16h-8Zm11 0h8v16h-8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yw7nsuu5z) {
  d: path("M4.5 14.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-6h.01m8.99 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-6h.01");
}

</style>
