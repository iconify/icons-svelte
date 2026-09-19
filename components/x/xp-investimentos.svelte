<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="em9o_c-lg"/><path class="iazoepo-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:xp-investimentos" {...props}></Icon>
<style>
:global(.em9o_c-lg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M27.715 27.383l-7.558 10.015m7.558 0l-7.558-10.015");
}

:global(.iazoepo-p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.51 33.619a3.78 3.78 0 0 0 3.78 3.78h0a3.78 3.78 0 0 0 3.779-3.78v-2.457a3.78 3.78 0 0 0-3.78-3.779h0a3.78 3.78 0 0 0-3.779 3.78m0-3.78V42.5");
}

</style>
