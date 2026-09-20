<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4qft3b0u"/><path class="ewcibzbps"/><path class="qxhe48bjs"/><path class="ulbp0sbur"/><path class="hvp96bbhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treehouse-duotone-thin" {...props}></Icon>
<style>
:global(.ewcibzbps) {
  d: path("M5 14V9l7 -7 7 7v5Z");
}

:global(.f4qft3b0u) {
  fill: currentColor;
  d: path("M5 14V9l7 -7 7 7v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvp96bbhp) {
  d: path("m12 18 4 -4");
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.ulbp0sbur) {
  d: path("m12 18 -4 -4");
}

</style>
