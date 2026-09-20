<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="myekf3bzc"/><path class="cpvmwnddk"/><path class="vr5wd2g-l"/><path class="q1ha9bc_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:user-prompt-outline-regular" {...props}></Icon>
<style>
:global(.cpvmwnddk) {
  d: path("M2 19a5 5 0 0 1 10 0");
}

:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q1ha9bc_u) {
  d: path("M13.5 17H22");
}

:global(.vr5wd2g-l) {
  d: path("M13.5 11a3 3 0 0 1 3 -3H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-2.5a3 3 0 0 1 -3 -3");
}

</style>
