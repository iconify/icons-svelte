<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7mc2oblu"/><path class="d7l74gtdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:window-arrow-slit" {...props}></Icon>
<style>
:global(.d7l74gtdm) {
  d: path("M10.5 6.75h3v10.5h-3ZM3 10h4.5m9 4H21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w7mc2oblu) {
  d: path("M3 4h18v16H3Z");
}

</style>
