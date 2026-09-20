<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cjm330b0r"/><path class="n-7xnfbas"/><path class="vtc00ob6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skill-badge-duotone-regular" {...props}></Icon>
<style>
:global(.cjm330b0r) {
  fill: currentColor;
  d: path("m12 3 7 7v4l-7 7 -7 -7v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n-7xnfbas) {
  d: path("m12 3 7 7v4l-7 7 -7 -7v-4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vtc00ob6f) {
  d: path("m8 10 3 3 5 -5");
}

</style>
