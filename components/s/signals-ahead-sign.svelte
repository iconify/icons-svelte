<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="i0u5p2m7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:signals-ahead-sign" {...props}></Icon>
<style>
:global(.dh2jzoboc) {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

:global(.i0u5p2m7x) {
  d: path("M9.75 6.25h4.5v11.5h-4.5ZM12 9h.01M12 12h.01M12 15h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
