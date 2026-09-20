<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vq8sxnw0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tv-20-filled" {...props}></Icon>
<style>
:global(.vq8sxnw0h) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm3.5 10a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1z");
}

</style>
