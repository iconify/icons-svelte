<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xr-g-ebyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:web-asset-20-regular" {...props}></Icon>
<style>
:global(.xr-g-ebyo) {
  fill: currentColor;
  d: path("M6.5 6a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zM6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2z");
}

</style>
