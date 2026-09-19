<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5_gnccui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-drafts" {...props}></Icon>
<style>
:global(.q5_gnccui) {
  fill: currentColor;
  d: path("M21.99 6.86L12 1L2 6.86V20h20zM12 13L3.74 7.84L12 3l8.26 4.84z");
}

</style>
