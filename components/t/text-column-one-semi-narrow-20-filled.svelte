<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u75f-pb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-semi-narrow-20-filled" {...props}></Icon>
<style>
:global(.u75f-pb5z) {
  fill: currentColor;
  d: path("M6.75 5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5zM6 11.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75M6.75 14a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5z");
}

</style>
