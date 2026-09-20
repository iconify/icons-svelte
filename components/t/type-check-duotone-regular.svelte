<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uykxl6bsn"/><path class="eaysgub_v"/><path class="z_smtp8xa"/><path class="atcmxjbma"/><path class="p4idz7btn"/><path class="h6srt4n9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-check-duotone-regular" {...props}></Icon>
<style>
:global(.atcmxjbma) {
  d: path("M4 5h12");
}

:global(.eaysgub_v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h6srt4n9a) {
  d: path("m14 15 3 3 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p4idz7btn) {
  d: path("M10 5v10");
}

:global(.uykxl6bsn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_smtp8xa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 15 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
