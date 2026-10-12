<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="puogjtdng"/><path class="i3pd7abnj"/><path class="b90vbpbke"/><path class="d74424b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wallet-x-sharp" {...props}></Icon>
<style>
:global(.b90vbpbke) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.9 13h.01");
}

:global(.d74424b-z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.75h4.5");
}

:global(.i3pd7abnj) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 10.25h4.5v5.5h-4.5a2.75 2.75 0 0 1 0-5.5Z");
}

:global(.puogjtdng) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v14.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
