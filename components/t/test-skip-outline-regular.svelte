<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="l-z02yb4d"/><path class="l3jp1qxjq"/><path class="gi1z84b3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-skip-outline-regular" {...props}></Icon>
<style>
:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.gi1z84b3y) {
  d: path("M14.5 13.5v5");
}

:global(.l-z02yb4d) {
  d: path("M11 5v5l2.5 -2.5Z");
}

:global(.l3jp1qxjq) {
  d: path("M9.5 13.5 12 16l-2.5 2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
