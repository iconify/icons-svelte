<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyvm7xbin"/><path class="j7l757b5u"/><path class="lo7kp72nh"/><path class="mjuhvrbig"/><path class="zg6stybep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surrogate-key-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7l757b5u) {
  fill: currentColor;
  d: path("M16 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.mjuhvrbig) {
  d: path("M9 8h9v9");
}

:global(.yyvm7xbin) {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zg6stybep) {
  d: path("M16 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
