<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ix-fbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-panorama" {...props}></Icon>
<style>
:global(.h7ix-fbmf) {
  fill: currentColor;
  d: path("M23 20V4H1v16zM8.5 12.5l2.5 3.01L14.5 11l4.5 6H5z");
}

</style>
