<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kr1c9wbph"/><path class="y6jkgnv3w"/><path class="uhddw3bue"/><path class="a9sr_7l2f"/><path class="liclahiaz"/><path class="d-tnphbnb"/><path class="mq1k2k45m"/><path class="i8t3_pbsa"/><path class="cuxt49b2j"/><path class="vs9lv0b4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:supervisor-duotone-regular" {...props}></Icon>
<style>
:global(.a9sr_7l2f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 10.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cuxt49b2j) {
  d: path("m9.5 10.5 -2 2");
}

:global(.d-tnphbnb) {
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
}

:global(.i8t3_pbsa) {
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
}

:global(.kr1c9wbph) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.liclahiaz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14.5 10.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mq1k2k45m) {
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uhddw3bue) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vs9lv0b4s) {
  d: path("m14.5 10.5 2 2");
}

:global(.y6jkgnv3w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
