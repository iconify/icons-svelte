<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ibuanu9pl"/><path class="xavluccpn"/><path class="j5cmolbru"/><path class="zrbvwbtjz"/><path class="wg81b4bij"/><path class="hvbgd99_z"/><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-turbine-duotone-regular" {...props}></Icon>
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

:global(.hvbgd99_z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11 9 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ibuanu9pl) {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j5cmolbru) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.wg81b4bij) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 9 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xavluccpn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zrbvwbtjz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
