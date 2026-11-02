<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k56d62gzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-bulk" {...props}></Icon>
<style>
:global(.k56d62gzl) {
  fill: currentColor;
  d: path("M5 5a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0h-4v12h1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2h1V6H7a1 1 0 0 1-2 0Z");
}

</style>
