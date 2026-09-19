<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p4ox9he1j"/><g class="y9tr6bcfx"><circle class="setjp3boe"/><path class="gf8vpl6gp"/></g><path class="yb8u59msv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:video-mp3-converter" {...props}></Icon>
<style>
:global(.gf8vpl6gp) {
  d: path("M38.508 29.488V14h4.008");
}

:global(.p4ox9he1j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.396 9.589c-8.374-6.71-20.602-5.362-27.312 3.012s-5.362 20.603 3.012 27.313c7.729 6.193 18.879 5.582 25.884-1.418");
}

:global(.setjp3boe) {
  cx: 33.996px;
  cy: 29.488px;
  r: 4.512px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yb8u59msv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.676 3.841l1.72 5.748l-5.748 1.721");
}

</style>
