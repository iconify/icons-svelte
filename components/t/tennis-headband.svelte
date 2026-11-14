<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="izy1-ubsf"/><path class="xlgoald2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tennis-headband" {...props}></Icon>
<style>
:global(.izy1-ubsf) {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm-1 12.5c0-2 3.25-3.25 7.5-3.25s7.5 1.25 7.5 3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xlgoald2i) {
  d: path("M6.5 5.5q5.5 2 11 0m-12 3q6.5 2 13 0");
}

</style>
