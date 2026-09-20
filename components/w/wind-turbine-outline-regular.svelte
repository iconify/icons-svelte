<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-turbine-outline-regular" {...props}></Icon>
<style>
:global(.az1hpy9gr) {
  d: path("M12 9v12");
}

:global(.dzjr38hwz) {
  d: path("m13 9 5 5");
}

:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.s74j1ubnz) {
  d: path("m11 9 -5 5");
}

</style>
