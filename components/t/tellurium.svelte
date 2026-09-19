<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l5wb0ubuc"/><path class="fkftdxb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tellurium" {...props}></Icon>
<style>
:global(.fkftdxb4x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.65 31.103a4.75 4.75 0 0 1-4.128 2.397h0a4.75 4.75 0 0 1-4.75-4.75v-3.087a4.75 4.75 0 0 1 4.75-4.75h0a4.75 4.75 0 0 1 4.75 4.75v1.543h-9.5");
}

:global(.l5wb0ubuc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-24.772 9h12.588m-6.294 19v-19");
}

</style>
