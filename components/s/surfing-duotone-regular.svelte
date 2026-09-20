<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p3m_o3bwf"/><path class="f3mcq1ban"/><path class="pynu7yt3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surfing-duotone-regular" {...props}></Icon>
<style>
:global(.f3mcq1ban) {
  d: path("M12 3c3 3 4 8 3 12H9c-1 -4 0 -9 3 -12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3m_o3bwf) {
  fill: currentColor;
  d: path("M12 3c3 3 4 8 3 12H9c-1 -4 0 -9 3 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pynu7yt3k) {
  d: path("M3 19c3 -2 6 2 9 0s6 2 9 0");
}

</style>
