<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfwk4ub9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-fill-round" {...props}></Icon>
<style>
:global(.nfwk4ub9u) {
  fill: currentColor;
  d: path("M22 16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5Zm-5 3a3 3 0 0 0 3-3V9H10v10Z");
}

</style>
