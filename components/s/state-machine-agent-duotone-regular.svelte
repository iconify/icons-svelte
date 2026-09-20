<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xa771-t-o"/><path class="f8es0kdly"/><path class="lvy4ugbrg"/><path class="ugdbidcqi"/><path class="ik3tfcbzx"/><path class="sim8sii7h"/><path class="a20judcsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:state-machine-agent-duotone-regular" {...props}></Icon>
<style>
:global(.a20judcsg) {
  d: path("m10.5 10.5 3 3");
}

:global(.f8es0kdly) {
  fill: currentColor;
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ik3tfcbzx) {
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lvy4ugbrg) {
  fill: currentColor;
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sim8sii7h) {
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

:global(.xa771-t-o) {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
