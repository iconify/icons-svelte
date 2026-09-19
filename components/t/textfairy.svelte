<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygqt55iez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:textfairy" {...props}></Icon>
<style>
:global(.ygqt55iez) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.296 5.5H5.5v3.796m37 0V5.5h-3.796m0 37H42.5v-3.796m-37 0V42.5h3.796m3.189-31.344h23.028M24.16 36.843V11.156");
}

</style>
