<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mbiybfboe"/><path class="ohvna4b7v"/><path class="by0--npeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tablet" {...props}></Icon>
<style>
:global(.by0--npeg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.124 4.501h21.752a3.345 3.345 0 0 1 3.352 3.338v32.309a3.345 3.345 0 0 1-3.337 3.353H13.124a3.345 3.345 0 0 1-3.352-3.338V7.853A3.345 3.345 0 0 1 13.109 4.5z");
}

:global(.mbiybfboe) {
  fill: currentColor;
  d: path("M24.75 40.97a.75.75 0 1 1-.75-.75a.75.75 0 0 1 .75.751");
}

:global(.ohvna4b7v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 8.903h23v30h-23z");
}

</style>
