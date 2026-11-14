<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w8uxmzbsa"/><path class="u21ay5bih"/><path class="o950tob6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transport-museum" {...props}></Icon>
<style>
:global(.o950tob6b) {
  d: path("M14.5 19.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.u21ay5bih) {
  d: path("M16 7V4h2v4.75m-4.5 9.75v-2a1 1 0 0 1 1-1l1.5-2h3.5l1.5 2a1 1 0 0 1 1 1v2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w8uxmzbsa) {
  d: path("M10.66 20.5H4v-10l8-7l8 7v.24");
}

</style>
