<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c5_8ftbtf"/><path class="km2_vvbqp"/><path class="e11fkcb8q"/><path class="v901idbpj"/><path class="kgtbp50fa"/><path class="exx4qg62z"/><path class="o8od38cnm"/><path class="z5iv6lbtc"/><path class="xaedo1bnv"/><path class="omq19fbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunset-header-duotone-bold" {...props}></Icon>
<style>
:global(.c5_8ftbtf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 15a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e11fkcb8q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4.5V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.exx4qg62z) {
  d: path("M7 15a5 5 0 0 1 10 0");
}

:global(.kgtbp50fa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 8 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km2_vvbqp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.omq19fbzw) {
  d: path("m19 8 -2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v901idbpj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 8 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaedo1bnv) {
  d: path("m5 8 2 2");
}

:global(.z5iv6lbtc) {
  d: path("M12 4.5V7");
}

</style>
