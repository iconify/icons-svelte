<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mlf-c4bcp"/><path class="bsr-upbww"/><path class="tuwz4b-ff"/><path class="x0thx_b6v"/><path class="br1blbchr"/><path class="t72hs-46k"/><path class="apq8ywbbc"/><path class="e0v4wgb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-strong-duotone-thin" {...props}></Icon>
<style>
:global(.apq8ywbbc) {
  d: path("M3 15h14");
}

:global(.br1blbchr) {
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
}

:global(.bsr-upbww) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e0v4wgb4v) {
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mlf-c4bcp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t72hs-46k) {
  d: path("M3 11h17");
}

:global(.tuwz4b-ff) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x0thx_b6v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
