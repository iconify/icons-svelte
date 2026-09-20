<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pue18lbrd"/><path class="k-a3mgzwy"/><path class="u5rn05amy"/><path class="dt6t4bcmu"/><path class="v99mbcczu"/><path class="brz3--krt"/><path class="n8z3lbl9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:true-false-duotone-thin" {...props}></Icon>
<style>
:global(.brz3--krt) {
  d: path("m15 14 4 4");
}

:global(.dt6t4bcmu) {
  d: path("m5 8 2 2 4 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-a3mgzwy) {
  fill: currentColor;
  d: path("M13 12h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n8z3lbl9h) {
  d: path("m19 14 -4 4");
}

:global(.pue18lbrd) {
  fill: currentColor;
  d: path("M3 4h8v8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u5rn05amy) {
  d: path("M3 4h8v8H3Z");
}

:global(.v99mbcczu) {
  d: path("M13 12h8v8h-8Z");
}

</style>
