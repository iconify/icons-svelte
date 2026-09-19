<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg3mi0baa"/><path class="qfa8ccc8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-polyline" {...props}></Icon>
<style>
:global(.hg3mi0baa) {
  fill: currentColor;
  d: path("M12 4h2v2h-2zM7 14H5v-2h2zm12 6h-2v-2h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.qfa8ccc8k) {
  fill: currentColor;
  d: path("M15 16v1.26l-6-3v-3.17L11.7 8H16V2h-6v4.9L7.3 10H3v6h5l7 3.5V22h6v-6zM12 4h2v2h-2zM7 14H5v-2h2zm12 6h-2v-2h2z");
}

</style>
