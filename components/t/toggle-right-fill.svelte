<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mutmsxm1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:toggle-right-fill" {...props}></Icon>
<style>
:global(.mutmsxm1f) {
  fill: currentColor;
  d: path("M176 56H80a72 72 0 0 0 0 144h96a72 72 0 0 0 0-144m0 112a40 40 0 1 1 40-40a40 40 0 0 1-40 40");
}

</style>
