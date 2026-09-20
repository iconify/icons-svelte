<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nu-uxtbks"/><path class="ni8b__upb"/><path class="rwh0lgbpm"/><path class="gcy6xobcc"/><path class="snl1mwbpd"/><path class="hxmy65bqc"/><path class="v15ibfbyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spend-alert-duotone-regular" {...props}></Icon>
<style>
:global(.gcy6xobcc) {
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.hxmy65bqc) {
  d: path("M19 6.5v5");
}

:global(.ni8b__upb) {
  fill: currentColor;
  d: path("M7 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.nu-uxtbks) {
  fill: currentColor;
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rwh0lgbpm) {
  fill: currentColor;
  d: path("M18 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.snl1mwbpd) {
  d: path("M7 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.v15ibfbyr) {
  d: path("M18 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
