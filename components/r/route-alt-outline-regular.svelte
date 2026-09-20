<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o5r_prbgx"/><path class="ai0e6e9tr"/><path class="da8_tjeku"/><path class="woyykhguz"/><path class="wpz4ckbwy"/><path class="fy2_4cbcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:route-alt-outline-regular" {...props}></Icon>
<style>
:global(.ai0e6e9tr) {
  d: path("M16 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.da8_tjeku) {
  d: path("M5 9v7h11v3");
}

:global(.fy2_4cbcf) {
  d: path("M19 11v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o5r_prbgx) {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.woyykhguz) {
  d: path("M9 5h3.5");
}

:global(.wpz4ckbwy) {
  d: path("M15.5 5H19v3");
}

</style>
