<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="qbzh-xbpw"/><path class="y49yakb9n"/><path class="uk7acdcay"/><path class="b4de0eyhw"/><path class="bo51iypxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:socket-open-duotone-regular" {...props}></Icon>
<style>
:global(.b4de0eyhw) {
  d: path("M16 4h4v16h-4");
}

:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qbzh-xbpw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4H4v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uk7acdcay) {
  d: path("M8 4H4v16h4");
}

:global(.y49yakb9n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
