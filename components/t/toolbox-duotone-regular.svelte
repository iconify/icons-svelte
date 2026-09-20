<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qb7dqkbxu"/><path class="oy6b_1b_a"/><path class="ltriwmbuu"/><path class="yngda3bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toolbox-duotone-regular" {...props}></Icon>
<style>
:global(.ltriwmbuu) {
  d: path("M8 10a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oy6b_1b_a) {
  d: path("M3 20V10h18v10Z");
}

:global(.qb7dqkbxu) {
  fill: currentColor;
  d: path("M3 20V10h18v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>
