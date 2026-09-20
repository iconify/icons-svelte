<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="spgu4hbor"/><path class="zxxlzlquy"/><path class="hgkl2obfa"/><path class="yrnos1b9y"/><path class="sxoexqb3p"/><path class="yot8r9baw"/><path class="rq7ulnb_u"/><path class="a-yudr8sp"/><path class="t6gygp83h"/><path class="qml5wxbjt"/><path class="ba_uovbta"/><path class="bz2_dqbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sample-rows-duotone-thin" {...props}></Icon>
<style>
:global(.a-yudr8sp) {
  d: path("M8 9.5h13");
}

:global(.ba_uovbta) {
  d: path("M3.5 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.bz2_dqbae) {
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hgkl2obfa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qml5wxbjt) {
  d: path("M8 21h13");
}

:global(.rq7ulnb_u) {
  d: path("M8 4h13");
}

:global(.spgu4hbor) {
  fill: currentColor;
  d: path("M3.5 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sxoexqb3p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t6gygp83h) {
  d: path("M8 15.5h13");
}

:global(.yot8r9baw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yrnos1b9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zxxlzlquy) {
  fill: currentColor;
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
