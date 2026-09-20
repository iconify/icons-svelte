<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="agpw-tbwq"/><path class="b51mjibkt"/><path class="kjjsomb8f"/><path class="p3zi2gbag"/><path class="na65nl0eo"/><path class="cs3crkb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:static-stability-duotone-regular" {...props}></Icon>
<style>
:global(.agpw-tbwq) {
  fill: currentColor;
  d: path("M8 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.b51mjibkt) {
  d: path("M8 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.cs3crkb9d) {
  d: path("m13.5 18 -2 2 2 2");
}

:global(.kjjsomb8f) {
  d: path("M3 4h7.5");
}

:global(.na65nl0eo) {
  d: path("M13.5 20H21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3zi2gbag) {
  d: path("m10.5 2 2 2 -2 2");
}

</style>
