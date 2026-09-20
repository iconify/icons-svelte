<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8-rvrwyp"/><path class="lgz_om1xp"/><path class="cqx_5fa1v"/><path class="y18a3dbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vector-duotone-thin" {...props}></Icon>
<style>
:global(.cqx_5fa1v) {
  d: path("M3 21 20 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lgz_om1xp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 4h7v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w8-rvrwyp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y18a3dbyh) {
  d: path("M13 4h7v7");
}

</style>
