<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uyc7v--_q"/><path class="a_bujybtt"/><path class="u2rqbibrm"/><path class="uof3uv2_w"/><path class="uadcs425n"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snowfall-duotone-regular" {...props}></Icon>
<style>
:global(.a_bujybtt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 10.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u2rqbibrm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uadcs425n) {
  d: path("M16 10.5v7m-3.5 0 7 -7");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.uof3uv2_w) {
  d: path("M8 3.5v7m-3.5 0 7 -7");
}

:global(.uyc7v--_q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
