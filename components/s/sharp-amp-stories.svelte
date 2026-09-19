<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxrmu3bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-amp-stories" {...props}></Icon>
<style>
:global(.dxrmu3bmu) {
  fill: currentColor;
  d: path("M7 4h10v15H7zM3 6h2v11H3zm16 0h2v11h-2z");
}

</style>
