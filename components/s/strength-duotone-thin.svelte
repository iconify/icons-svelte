<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7k-2fb3i"/><path class="q0c4v9qfz"/><path class="hz4hedb0s"/><path class="dfkdfcs-l"/><path class="r8-d-gbco"/><path class="n4avueb2x"/><path class="xxhou8bla"/><path class="u-hehrbeq"/><path class="tum88bbiw"/><path class="t407nkbfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:strength-duotone-thin" {...props}></Icon>
<style>
:global(.dfkdfcs-l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hz4hedb0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 17h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n4avueb2x) {
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.o7k-2fb3i) {
  fill: currentColor;
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q0c4v9qfz) {
  fill: currentColor;
  d: path("M14 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r8-d-gbco) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t407nkbfi) {
  d: path("m9 7 3 -3 3 3");
}

:global(.tum88bbiw) {
  d: path("M12 12V4");
}

:global(.u-hehrbeq) {
  d: path("M10 17h4");
}

:global(.xxhou8bla) {
  d: path("M14 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
