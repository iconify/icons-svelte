<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r02mcwb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-right-fill-round" {...props}></Icon>
<style>
:global(.r02mcwb0y) {
  fill: currentColor;
  d: path("M7 21a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21Zm-3-5a3.004 3.004 0 0 0 3 3h7V9H4Z");
}

</style>
