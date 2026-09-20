<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ihyvscpag"/><path class="pkomvsbso"/><path class="cqx_5fa1v"/><path class="y18a3dbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vector-duotone-bold" {...props}></Icon>
<style>
:global(.cqx_5fa1v) {
  d: path("M3 21 20 4");
}

:global(.ihyvscpag) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pkomvsbso) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 4h7v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y18a3dbyh) {
  d: path("M13 4h7v7");
}

</style>
