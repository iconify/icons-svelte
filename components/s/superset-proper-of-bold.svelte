<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="za9stvb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:superset-proper-of-bold" {...props}></Icon>
<style>
:global(.za9stvb_y) {
  fill: currentColor;
  d: path("M228 128a92.1 92.1 0 0 1-92 92H64a12 12 0 0 1 0-24h72a68 68 0 0 0 0-136H64a12 12 0 0 1 0-24h72a92.1 92.1 0 0 1 92 92");
}

</style>
