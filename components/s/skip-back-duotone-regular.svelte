<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nk6qfwujr"/><path class="ay0-xnb_u"/><path class="e80on1hgs"/><path class="azgrucbqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skip-back-duotone-regular" {...props}></Icon>
<style>
:global(.ay0-xnb_u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.azgrucbqu) {
  d: path("M7 5v14");
}

:global(.e80on1hgs) {
  d: path("m18 5 -7 7 7 7");
}

:global(.nk6qfwujr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
