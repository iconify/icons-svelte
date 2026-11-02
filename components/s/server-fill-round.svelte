<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g-q6bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-fill-round" {...props}></Icon>
<style>
:global(.u5g-q6bcn) {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-1 7h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
