<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="edyse0l7n"/><path class="qq3_d4bjv"/><path class="yf2jpezvj"/></g><path class="oek7ajalh"/><path class="de6dkbcfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zipme" {...props}></Icon>
<style>
:global(.de6dkbcfb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.366 29.996a6.783 6.783 0 0 1 6.783 6.783h0a.964.964 0 0 1-.964.964h0h-11.668a.964.964 0 0 1-.965-.964h0a6.783 6.783 0 0 1 6.783-6.783zm-5.857-1.011l1.929 2.263m9.786-2.263l-1.93 2.263");
}

:global(.edyse0l7n) {
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.oek7ajalh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.605 35.853a.949.949 0 1 1 0-1.898a.949.949 0 0 1 0 1.898m5.538 0a.949.949 0 1 1 0-1.898a.949.949 0 0 1 0 1.898");
}

:global(.qq3_d4bjv) {
  d: path("M10.368 7.447v1.948l.974.974h1.947l.974-.974V7.447");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yf2jpezvj) {
  d: path("m12.316 10.368l-.974.974v1.947l.974.974l.973-.974v-1.947zm-1.948-2.921h3.895m-2.921 0V5.5h0m1.948 1.947V5.5m-1.948 9.737V42.5m1.948-27.263V42.5m-1.948-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.921h1.947m-1.947-2.922h1.947m16.553-4.868h5.842m-2.921-2.921v5.842");
}

</style>
