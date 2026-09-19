<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w9pqv6blq"/><path class="pljhhxjri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tigad" {...props}></Icon>
<style>
:global(.pljhhxjri) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.433 32.209l6.374-11.039l6.375 11.039zm6.375-21.799h-5.616L5.5 37.59h5.616");
}

:global(.w9pqv6blq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.808 10.41L11.116 37.59H42.5z");
}

</style>
