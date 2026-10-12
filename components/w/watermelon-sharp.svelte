<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i8ltxosao"/><path class="pnopb7b7a"/><path class="bdflu961o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:watermelon-sharp" {...props}></Icon>
<style>
:global(.bdflu961o) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M12 12.25h.01M15 10h.01");
}

:global(.i8ltxosao) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h18.5a9.25 9.25 0 0 1-18.5 0Z");
}

:global(.pnopb7b7a) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.75a6.5 6.5 0 0 0 13 0");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
