<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zy1hjcrps"/><path class="u5jltjbuw"/><path class="ixra9kslx"/><path class="lfw9kzb2z"/><path class="uy5j3ks5u"/><path class="ok9ioqb8x"/><path class="pl-e7wb3s"/><path class="zuzyjabxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skating-duotone-regular" {...props}></Icon>
<style>
:global(.ixra9kslx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lfw9kzb2z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.pl-e7wb3s) {
  d: path("M6 14v3");
}

:global(.u5jltjbuw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uy5j3ks5u) {
  d: path("M6 4v10h12v-3");
}

:global(.zuzyjabxh) {
  d: path("M18 14v3");
}

:global(.zy1hjcrps) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 4v10h12v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
