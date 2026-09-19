<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="unu61ibdy"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vectorpinball" {...props}></Icon>
<style>
:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.unu61ibdy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 25.24l11.674-4.689m3.268 15.058L42.5 26.752m-14.718-15.65a2.51 2.51 0 1 1 .002 5.019a2.51 2.51 0 0 1-.003-5.019z");
}

</style>
