<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhjp6nbql"/><path class="oug_9fb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-browse-gallery" {...props}></Icon>
<style>
:global(.dhjp6nbql) {
  fill: currentColor;
  d: path("M9 3a9 9 0 1 0 .001 18.001A9 9 0 0 0 9 3m2.79 13.21L8 12.41V7h2v4.59l3.21 3.21z");
}

:global(.oug_9fb0s) {
  fill: currentColor;
  d: path("M17.99 3.52v2.16A6.99 6.99 0 0 1 22 12c0 2.79-1.64 5.2-4.01 6.32v2.16C21.48 19.24 24 15.91 24 12s-2.52-7.24-6.01-8.48");
}

</style>
