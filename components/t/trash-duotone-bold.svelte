<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hyr-98bnb"/><path class="rnnki-bvy"/><path class="k6nj2fbya"/><path class="ew8lc9fxa"/><path class="fpad0ccyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trash-duotone-bold" {...props}></Icon>
<style>
:global(.ew8lc9fxa) {
  d: path("M10 11v6");
}

:global(.fpad0ccyb) {
  d: path("M14 11v6");
}

:global(.hyr-98bnb) {
  fill: currentColor;
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.rnnki-bvy) {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
