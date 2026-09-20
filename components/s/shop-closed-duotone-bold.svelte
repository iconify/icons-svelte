<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="ixfun3jnw"/><path class="bqauhbcsv"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="gjjx1zbjy"/><path class="a5c-jhmhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shop-closed-duotone-bold" {...props}></Icon>
<style>
:global(.a5c-jhmhz) {
  d: path("m14 13 -4 4");
}

:global(.bqauhbcsv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 13 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fmbgtccaf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjjx1zbjy) {
  d: path("m10 13 4 4");
}

:global(.ixfun3jnw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 13 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

:global(.z6qs6gbnt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
