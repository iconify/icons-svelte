<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w7hn9_bfn"/><path class="v2kkeqbgn"/><path class="hzpqnlmob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tripeaks" {...props}></Icon>
<style>
:global(.hzpqnlmob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.v2kkeqbgn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.5 33.157l11.58-10.911l12.213 12.072");
}

:global(.w7hn9_bfn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.509 27.107l14.533-13.425l6.021 5.991m-5.235 6.157l7.264-8.477L39.5 27.1");
}

</style>
