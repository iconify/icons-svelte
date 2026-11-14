<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="unogj3s4j"/><path class="bia11_bye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:volunteer-check-in" {...props}></Icon>
<style>
:global(.bia11_bye) {
  d: path("M8.5 2.5h7v4h-7Zm-.5 11l3 3l5.5-6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unogj3s4j) {
  d: path("M4 4.5h16v17H4Z");
}

</style>
