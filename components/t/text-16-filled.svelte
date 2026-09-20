<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="atzfbjl7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-16-filled" {...props}></Icon>
<style>
:global(.atzfbjl7h) {
  fill: currentColor;
  d: path("M2.5 2.75A.75.75 0 0 1 3.25 2h9a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0V3.5h-3v9h1.25a.75.75 0 0 1 0 1.5h-4a.75.75 0 0 1 0-1.5H7v-9H4v.75a.75.75 0 0 1-1.5 0z");
}

</style>
