<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="okqi2lbic"/><path class="dhnofza7v"/><path class="b-pphqpeq"/><path class="sfnyx4wnk"/><path class="j_w0smilt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volume-mount-duotone-bold" {...props}></Icon>
<style>
:global(.b-pphqpeq) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.dhnofza7v) {
  fill: currentColor;
  d: path("M10 9.5a3.5 1.5 0 0 1 7 0v6a3.5 1.5 0 0 1 -7 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j_w0smilt) {
  d: path("M10 9.5a3.5 1.5 0 0 1 7 0v6a3.5 1.5 0 0 1 -7 0Z");
}

:global(.okqi2lbic) {
  fill: currentColor;
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfnyx4wnk) {
  d: path("M6 6v14");
}

</style>
