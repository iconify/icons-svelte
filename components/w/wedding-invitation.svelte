<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m2e6babgl"/><path class="qc7u9l3jg"/><path class="zdgxhjbxf"/><path class="a-_fbgbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wedding-invitation" {...props}></Icon>
<style>
:global(.a-_fbgbci) {
  d: path("M10.75 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.m2e6babgl) {
  d: path("M2.5 10h19v11h-19Z");
}

:global(.qc7u9l3jg) {
  d: path("m5 10l7 5l7-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdgxhjbxf) {
  d: path("M6.25 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
