<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g3dgjwbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wifi-none-light" {...props}></Icon>
<style>
:global(.g3dgjwbxu) {
  fill: currentColor;
  d: path("M138 204a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
