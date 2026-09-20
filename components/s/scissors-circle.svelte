<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="whkemmbou"/><path class="ssf41ebvy"/><path class="gl9rhfb6u"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:scissors-circle" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gl9rhfb6u) {
  d: path("M9.793 14.293a1 1 0 1 0 1.414 1.414l8.5-8.5a1 1 0 0 0-1.414-1.414z");
}

:global(.kphejjb8s) {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.ssf41ebvy) {
  d: path("M19.707 18.293a1 1 0 0 1-1.414 1.414l-8.5-8.5a1 1 0 0 1 1.414-1.414z");
}

:global(.whkemmbou) {
  fill-rule: evenodd;
  d: path("M5 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M5 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
