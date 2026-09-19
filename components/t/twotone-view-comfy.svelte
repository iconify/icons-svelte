<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmxnqfbcd"/><path class="jik9c9bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-view-comfy" {...props}></Icon>
<style>
:global(.jik9c9bfo) {
  fill: currentColor;
  d: path("M2 4v16h20V4zm6 14H4v-5h4zm12 0H10v-5h10zm0-7H4V6h16z");
}

:global(.mmxnqfbcd) {
  fill: currentColor;
  d: path("M10 18h10v-5H10zM4 6v5h16V6zm0 12h4v-5H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
