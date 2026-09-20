<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="r7xk8o29f"/><path class="rw6ho_bav"/><path class="l23it1b0d"/><path class="g_k4zfu5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surrogate-map-outline-regular" {...props}></Icon>
<style>
:global(.g_k4zfu5d) {
  d: path("M14 15h6");
}

:global(.l23it1b0d) {
  d: path("M6 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
