<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6lzdw25c"/><path class="eo43fxtwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:video-180" {...props}></Icon>
<style>
:global(.eo43fxtwk) {
  d: path("m10 9.5l5 2.5l-5 2.5Z");
}

:global(.k6lzdw25c) {
  d: path("M3 4.5q9 4.5 18 0v15q-9-4.5-18 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
