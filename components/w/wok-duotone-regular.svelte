<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zev6zlbze"/><path class="vt8fxebuz"/><path class="q3b6j7bvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wok-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q3b6j7bvq) {
  d: path("M20 10c2 0 2 -4 -1 -4");
}

:global(.vt8fxebuz) {
  d: path("M4 10h16l-6 6h-4Z");
}

:global(.zev6zlbze) {
  fill: currentColor;
  d: path("M4 10h16l-6 6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
