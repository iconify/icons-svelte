<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl4t1zbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-warning-fill-round" {...props}></Icon>
<style>
:global(.fl4t1zbdc) {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm11 1a1 1 0 0 0-2 0v5a1 1 0 0 0 2 0Zm-1 7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
