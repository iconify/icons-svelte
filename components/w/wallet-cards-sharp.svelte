<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s1y-0r_6c"/><path class="p7z70mbyq"/><path class="kr9hw9brb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wallet-cards-sharp" {...props}></Icon>
<style>
:global(.kr9hw9brb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.9 14.25h.01");
}

:global(.p7z70mbyq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 11.5h4.5V17h-4.5a2.75 2.75 0 0 1 0-5.5Z");
}

:global(.s1y-0r_6c) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h12.5v4.5H5.25zm-2.5 4.5h18.5v14H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
