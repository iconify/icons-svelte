<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-1fccnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rows-fill-round" {...props}></Icon>
<style>
:global(.dv-1fccnt) {
  fill: currentColor;
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m0 10h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8");
}

</style>
