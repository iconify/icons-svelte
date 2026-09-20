<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qy9mzacrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-wide-20-regular" {...props}></Icon>
<style>
:global(.qy9mzacrn) {
  fill: currentColor;
  d: path("M3.5 5a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm0 3a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zM3 11.5a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5m.5 2.5a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1z");
}

</style>
