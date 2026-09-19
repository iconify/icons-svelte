<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erkjrklty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-pivot-table-chart" {...props}></Icon>
<style>
:global(.erkjrklty) {
  fill: currentColor;
  d: path("M21 5c0-1.1-.9-2-2-2h-9v5h11zM3 19c0 1.1.9 2 2 2h3V10H3zM3 5v3h5V3H5c-1.1 0-2 .9-2 2m15 4l-4 4h3v2c0 1.1-.9 2-2 2h-2v-3l-4 4l4 4v-3h2c2.21 0 4-1.79 4-4v-2h3z");
}

</style>
