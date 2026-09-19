<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kg2ncgb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zepp" {...props}></Icon>
<style>
:global(.kg2ncgb1o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.875 5.5H8.13c1.264 7.02 2.363 15.061 21.027 18.679C19.278 26.976 7.84 29.837 8.13 42.5h31.743");
}

</style>
