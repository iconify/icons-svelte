<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4iwgccyk"/><path class="eeysahb4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:volunteer-background-check" {...props}></Icon>
<style>
:global(.e4iwgccyk) {
  d: path("M10.8 18H2.5V3.5h18v8.8");
}

:global(.eeysahb4p) {
  d: path("M6 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1 7a2.75 2.75 0 0 1 5.5 0M13 8.5h4.5M13 12h3m-1.25 6l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
