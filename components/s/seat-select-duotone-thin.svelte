<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ehzfylb8o"/><path class="yce23gbyj"/><path class="yfxq4li_y"/><path class="okud9xj_d"/><path class="f7x_bjbhr"/><path class="ekx6x-33y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:seat-select-duotone-thin" {...props}></Icon>
<style>
:global(.ehzfylb8o) {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ekx6x-33y) {
  d: path("M14 9h4v6h-4Z");
}

:global(.f7x_bjbhr) {
  d: path("M6 9h4v6H6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.yce23gbyj) {
  fill: currentColor;
  d: path("M6 9h4v6H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yfxq4li_y) {
  fill: currentColor;
  d: path("M14 9h4v6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
