<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ptmdrqmnr"/><path class="as6g9lfvf"/><path class="s2f_5t2iz"/><path class="nbgsfjb6u"/><path class="tr6mw0eac"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trophy-cup-duotone-regular" {...props}></Icon>
<style>
:global(.as6g9lfvf) {
  d: path("M7 3h10v6c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.nbgsfjb6u) {
  d: path("M17 5c3 0 4 4 0 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ptmdrqmnr) {
  fill: currentColor;
  d: path("M7 3h10v6c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s2f_5t2iz) {
  d: path("M7 5c-3 0 -4 4 0 5");
}

:global(.tr6mw0eac) {
  d: path("M12 15v4");
}

</style>
