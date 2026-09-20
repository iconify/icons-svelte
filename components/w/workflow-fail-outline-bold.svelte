<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f21or-k3k"/><path class="gujomac1p"/><path class="v0w-kwjac"/><path class="bd2iewblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:workflow-fail-outline-bold" {...props}></Icon>
<style>
:global(.bd2iewblu) {
  d: path("m20 12 -7 7");
}

:global(.f21or-k3k) {
  d: path("M2 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.gujomac1p) {
  d: path("M6 10v6h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v0w-kwjac) {
  d: path("m13 12 7 7");
}

</style>
