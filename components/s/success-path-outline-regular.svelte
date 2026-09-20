<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e7pgrp-wx"/><path class="ns11or76z"/><path class="icgbjebhm"/><path class="cd_jjcbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:success-path-outline-regular" {...props}></Icon>
<style>
:global(.cd_jjcbbn) {
  d: path("m8 12 4 4h3");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.icgbjebhm) {
  d: path("m15 13 2 2 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns11or76z) {
  d: path("m8 12 4 -4h5");
}

</style>
