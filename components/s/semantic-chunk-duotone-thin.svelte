<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="ob5udfb7b"/><path class="t8qt32blf"/><path class="cwz65fbys"/><path class="uau0kschl"/><path class="o6a3qip5v"/><path class="xgrfb-bqu"/><path class="sixdm4bhp"/><path class="d223d_x9q"/><path class="nuz6-76is"/><path class="yngda3bvc"/><path class="ecph9tq5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:semantic-chunk-duotone-thin" {...props}></Icon>
<style>
:global(.cwz65fbys) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ecph9tq5i) {
  d: path("M3 18h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nuz6-76is) {
  d: path("M15 12h6");
}

:global(.o6a3qip5v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ob5udfb7b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sixdm4bhp) {
  d: path("M3 9h14");
}

:global(.t8qt32blf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uau0kschl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>
