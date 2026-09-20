<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="ld7zhcybq"/><path class="gob4qybps"/><path class="qcol0s9_v"/><path class="r0e633-if"/><path class="t1sjjacis"/><path class="u_41jqbcx"/><path class="h36909btm"/><path class="o759xmblc"/><path class="nvdm6duxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:version-control-duotone-thin" {...props}></Icon>
<style>
:global(.gob4qybps) {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h36909btm) {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ld7zhcybq) {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nvdm6duxk) {
  d: path("M8 6h4l4 4");
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.qcol0s9_v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r0e633-if) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6h4l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1sjjacis) {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.u_41jqbcx) {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vxdgzqbaj) {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
