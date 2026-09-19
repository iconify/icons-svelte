<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ic7gicc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vibb" {...props}></Icon>
<style>
:global(.ic7gicc9u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.868 8.558L24 25.28L17.132 8.558H5.5l12.684 30.884h11.632L42.5 8.558z");
}

</style>
