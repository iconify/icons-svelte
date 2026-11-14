<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pie290bbb"/><path class="gxed-2guk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:select-multiple" {...props}></Icon>
<style>
:global(.gxed-2guk) {
  d: path("M4.75 7L6 8.25l2.25-2.5M4.75 17L6 18.25l2.25-2.5M13 7h8m-8 10h8");
}

:global(.pie290bbb) {
  d: path("M3 3.5h7v7H3Zm0 10h7v7H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
