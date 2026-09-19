<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gienq2bsq"/><path class="c1o0jlbvv"/><path class="g_1vj4b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:upgrad" {...props}></Icon>
<style>
:global(.c1o0jlbvv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 35.187v-5.312h-5.312");
}

:global(.g_1vj4b-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 28.875c0 6.413 10.245 9.882 12.625 1");
}

:global(.gienq2bsq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.625 4.5v24.375C38.625 36.952 32.077 43.5 24 43.5S9.375 36.952 9.375 28.875V4.5z");
}

</style>
