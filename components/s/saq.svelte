<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cspgu_b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:saq" {...props}></Icon>
<style>
:global(.cspgu_b2e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.02 42.5h19.297m-12.369-7.267H8.346V5.5h31.308v29.733H26.461");
}

</style>
