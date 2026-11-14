<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4yjc8mwb"/><path class="c84mi2aph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:string-theory" {...props}></Icon>
<style>
:global(.c84mi2aph) {
  d: path("M5.5 12q1.5-3.75 3 0t3 0t3 0t3 0");
}

:global(.q4yjc8mwb) {
  d: path("M2.5 12a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
