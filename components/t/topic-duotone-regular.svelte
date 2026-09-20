<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e7uik3vez"/><path class="mq8aagbsg"/><path class="ezg__mbcy"/><path class="v9n654u9n"/><path class="kuk8yacoy"/><path class="n8h0kccut"/><path class="if5ft31dv"/><path class="mdci-mi7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:topic-duotone-regular" {...props}></Icon>
<style>
:global(.e7uik3vez) {
  fill: currentColor;
  d: path("M8 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ezg__mbcy) {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kuk8yacoy) {
  d: path("M8 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.mdci-mi7f) {
  d: path("M18 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mq8aagbsg) {
  fill: currentColor;
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n8h0kccut) {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v9n654u9n) {
  fill: currentColor;
  d: path("M18 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
