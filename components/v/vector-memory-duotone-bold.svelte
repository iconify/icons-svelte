<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m8c8atiya"/><path class="n0n63pb2v"/><path class="zyhfe-b-n"/><path class="r_r4jioyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vector-memory-duotone-bold" {...props}></Icon>
<style>
:global(.m8c8atiya) {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.r_r4jioyj) {
  d: path("M11.5 5H14v2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zyhfe-b-n) {
  d: path("m8 11 6 -6");
}

</style>
