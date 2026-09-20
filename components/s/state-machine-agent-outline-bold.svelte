<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugdbidcqi"/><path class="ik3tfcbzx"/><path class="sim8sii7h"/><path class="a20judcsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:state-machine-agent-outline-bold" {...props}></Icon>
<style>
:global(.a20judcsg) {
  d: path("m10.5 10.5 3 3");
}

:global(.ik3tfcbzx) {
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sim8sii7h) {
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
