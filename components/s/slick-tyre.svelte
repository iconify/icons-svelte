<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zi_car8rs"/><path class="d4zkzgjmg"/><path class="qs8m3xkod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:slick-tyre" {...props}></Icon>
<style>
:global(.d4zkzgjmg) {
  d: path("M10.5 3.5h3a8.5 8.5 0 0 1 0 17h-3");
}

:global(.qs8m3xkod) {
  d: path("M6.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zi_car8rs) {
  d: path("M2 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

</style>
