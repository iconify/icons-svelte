<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nc5x51_gv"/><path class="sh3phdbsj"/><path class="ou__26bde"/><path class="eiba9_b7g"/><path class="br1blbchr"/><path class="t72hs-46k"/><path class="apq8ywbbc"/><path class="e0v4wgb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-strong-duotone-regular" {...props}></Icon>
<style>
:global(.apq8ywbbc) {
  d: path("M3 15h14");
}

:global(.br1blbchr) {
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
}

:global(.e0v4wgb4v) {
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
}

:global(.eiba9_b7g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nc5x51_gv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ou__26bde) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sh3phdbsj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t72hs-46k) {
  d: path("M3 11h17");
}

</style>
