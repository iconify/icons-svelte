<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="itf4amkzs"/><path class="qv2dz9bzi"/><path class="u-td5sbea"/><path class="zqbjehbqe"/><path class="gcalxb98a"/><path class="xemj-cgvt"/><path class="ld2fqqd_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:salt-duotone-regular" {...props}></Icon>
<style>
:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.itf4amkzs) {
  fill: currentColor;
  d: path("M8 21V11l2 -2h4l2 2v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ld2fqqd_p) {
  d: path("M13 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qv2dz9bzi) {
  fill: currentColor;
  d: path("M9 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u-td5sbea) {
  fill: currentColor;
  d: path("M13 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xemj-cgvt) {
  d: path("M9 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zqbjehbqe) {
  d: path("M8 21V11l2 -2h4l2 2v10Z");
}

</style>
