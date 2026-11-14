<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="yqwjc9b7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:zone-30-sign" {...props}></Icon>
<style>
:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yqwjc9b7y) {
  d: path("M6.5 7h4.25l-2 3a2.25 2.25 0 1 1-1.5 3.75M13.75 7h3.75v7.5h-3.75ZM7 18h10");
}

</style>
