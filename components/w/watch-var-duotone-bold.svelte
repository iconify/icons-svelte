<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="esxx8sbse"/><path class="f51f0lbgo"/><path class="gqf09ibtk"/><path class="f-glw__bg"/><path class="z3e--kb9y"/><path class="ts70t37mn"/><path class="swzjdoakn"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:watch-var-duotone-bold" {...props}></Icon>
<style>
:global(.esxx8sbse) {
  fill: currentColor;
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f-glw__bg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f51f0lbgo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 9 5 -5h6l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gqf09ibtk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 9 5 5h6l5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.swzjdoakn) {
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ts70t37mn) {
  d: path("m4 9 5 5h6l5 -5");
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.z3e--kb9y) {
  d: path("m4 9 5 -5h6l5 5");
}

</style>
