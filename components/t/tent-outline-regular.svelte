<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i6clenrss"/><path class="vqy-3paam"/><path class="lf2ilxqms"/><path class="hc7fbd-jo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tent-outline-regular" {...props}></Icon>
<style>
:global(.hc7fbd-jo) {
  d: path("M4 19h16");
}

:global(.i6clenrss) {
  d: path("M2 16 12 6l10 10Z");
}

:global(.lf2ilxqms) {
  d: path("m12 11 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vqy-3paam) {
  d: path("m12 11 -5 5");
}

</style>
