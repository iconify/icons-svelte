<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j05_so5ho"/><path class="w08657bnd"/><path class="fufp8hb7p"/><path class="pfpu_3ppl"/><path class="gs502ibny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:x-ray-outline-bold" {...props}></Icon>
<style>
:global(.fufp8hb7p) {
  d: path("m10 8 -4 4");
}

:global(.gs502ibny) {
  d: path("m14 8 4 4");
}

:global(.j05_so5ho) {
  d: path("M3 16a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w08657bnd) {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
