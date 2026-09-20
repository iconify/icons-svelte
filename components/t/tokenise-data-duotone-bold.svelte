<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0jamibkm"/><path class="h3v02tb6u"/><path class="bn_pu6j-z"/><path class="l0zc9ibud"/><path class="nqn_onflm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tokenise-data-duotone-bold" {...props}></Icon>
<style>
:global(.bn_pu6j-z) {
  d: path("M20 7v13H4V4h5l3 3h4");
}

:global(.h3v02tb6u) {
  fill: currentColor;
  d: path("M7.5 15a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l0zc9ibud) {
  d: path("M8 10h8");
}

:global(.nqn_onflm) {
  d: path("M7.5 15a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2");
}

:global(.r0jamibkm) {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
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

</style>
