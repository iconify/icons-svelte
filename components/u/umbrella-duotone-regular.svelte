<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z3k3a4gqp"/><path class="uobmn7udv"/><path class="i_kkr1bqy"/><path class="mbefcubeg"/><path class="q20cs9bwz"/><path class="hjzvc-b8b"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="o162teb3v"/><path class="cr8isx4cy"/><path class="jzkjbccbo"/><path class="e2nq-yvbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:umbrella-duotone-regular" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.cr8isx4cy) {
  d: path("M15 12a3 3 0 0 1 -6 0");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.hjzvc-b8b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i_kkr1bqy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jzkjbccbo) {
  d: path("M21 12a3 3 0 0 1 -6 0");
}

:global(.mbefcubeg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o162teb3v) {
  d: path("M9 12a3 3 0 0 1 -6 0");
}

:global(.q20cs9bwz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t9gnp4b0n) {
  d: path("M3 12a9 9 0 0 1 18 0");
}

:global(.uobmn7udv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z3k3a4gqp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
