<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ihn1lmbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-wide-20-filled" {...props}></Icon>
<style>
:global(.ihn1lmbmv) {
  fill: currentColor;
  d: path("M3.75 5a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zM3 11.75a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75M3.75 14a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5z");
}

</style>
