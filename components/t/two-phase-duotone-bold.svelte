<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n3q4scbgf"/><path class="t67co0bam"/><path class="rs7k183fq"/><path class="h9i3bw3au"/><path class="n6_f133dv"/><path class="upuk2bbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:two-phase-duotone-bold" {...props}></Icon>
<style>
:global(.h9i3bw3au) {
  d: path("m5 8 2 2 3.5 -3.5");
}

:global(.n3q4scbgf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 8 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n6_f133dv) {
  d: path("m5 16 2 2 3.5 -3.5");
}

:global(.rs7k183fq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 5H18v14h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t67co0bam) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 16 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.upuk2bbmi) {
  d: path("M15.5 5H18v14h-2.5");
}

</style>
