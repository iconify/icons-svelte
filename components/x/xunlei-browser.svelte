<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ycvi2ubmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:xunlei-browser" {...props}></Icon>
<style>
:global(.ycvi2ubmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 8.393L29.2 21.85H18.8L5.5 8.393m37 31.214L29.2 26.15H18.8L5.5 39.607");
}

</style>
