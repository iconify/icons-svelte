<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i4fabudhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:wifi-4-20-regular" {...props}></Icon>
<style>
:global(.i4fabudhi) {
  fill: currentColor;
  d: path("M10.963 13.787a1.298 1.298 0 1 1-1.836 1.836a1.298 1.298 0 0 1 1.836-1.836");
}

</style>
