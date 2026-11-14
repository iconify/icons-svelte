<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tuv9yoo3g"/><path class="et55o7bxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:segment-compare" {...props}></Icon>
<style>
:global(.et55o7bxk) {
  fill: currentColor;
  d: path("M6.5 12V7.75a4.25 4.25 0 0 1 3.75 2Zm11 0V7.75A4.25 4.25 0 0 1 21.25 14Z");
}

:global(.tuv9yoo3g) {
  d: path("M2.25 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Zm11 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
