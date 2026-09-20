<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zgmc5964t"/><path class="o-zv_3bmm"/><path class="avq50ccio"/><path class="jl24-wygx"/><path class="fipykcbwt"/><path class="d210vyb8t"/><path class="ig2rw3qjx"/><path class="hs_3awbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shuffle-duotone-regular" {...props}></Icon>
<style>
:global(.avq50ccio) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h6l9 -9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d210vyb8t) {
  d: path("m18 13 3 3 -3 3");
}

:global(.fipykcbwt) {
  d: path("M3 7h6l9 9h3");
}

:global(.hs_3awbse) {
  d: path("m18 5 3 3 -3 3");
}

:global(.ig2rw3qjx) {
  d: path("M3 17h6l9 -9h3");
}

:global(.jl24-wygx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-zv_3bmm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zgmc5964t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h6l9 9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
