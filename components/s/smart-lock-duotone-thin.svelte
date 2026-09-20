<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttfv-r4jd"/><path class="i8fobbb8v"/><path class="vvghs3b3o"/><path class="eh2_kr33i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smart-lock-duotone-thin" {...props}></Icon>
<style>
:global(.eh2_kr33i) {
  d: path("M19 9q3 3 0 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i8fobbb8v) {
  d: path("M6 12v8h10v-8Z");
}

:global(.ttfv-r4jd) {
  fill: currentColor;
  d: path("M6 12v8h10v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vvghs3b3o) {
  d: path("M7 12a4 4 0 0 1 8 0");
}

</style>
