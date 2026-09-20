<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dscm1lbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-multiple-16-regular" {...props}></Icon>
<style>
:global(.dscm1lbwx) {
  fill: currentColor;
  d: path("M6 4a1 1 0 1 1-2 0a1 1 0 0 1 2 0M2 4a3 3 0 0 1 3-3h6a3 3 0 1 1 0 6H5a3 3 0 0 1-3-3m3-2a2 2 0 1 0 0 4h6a2 2 0 1 0 0-4zm6 10a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-9-1a3 3 0 0 1 3-3h6a3 3 0 1 1 0 6H5a3 3 0 0 1-3-3m3-2a2 2 0 1 0 0 4h6a2 2 0 1 0 0-4z");
}

</style>
