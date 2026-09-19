<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yaa0mvn2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:toya-go" {...props}></Icon>
<style>
:global(.yaa0mvn2y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.04 17.003A9.75 9.75 0 1 0 24 24m2.96 6.997A9.75 9.75 0 1 0 24 24m0 0h-9.75");
}

</style>
