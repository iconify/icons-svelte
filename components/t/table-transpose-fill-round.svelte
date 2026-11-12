<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tng9kfbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-transpose-fill-round" {...props}></Icon>
<style>
:global(.tng9kfbzx) {
  fill: currentColor;
  d: path("M13 2h6a3 3 0 1 1 0 6h-6a3 3 0 1 1 0-6M8 13v6a3 3 0 1 1-6 0v-6a3 3 0 1 1 6 0m7 2v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

</style>
