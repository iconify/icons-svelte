<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l4rvibcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-underline-character-u-20-filled" {...props}></Icon>
<style>
:global(.l4rvibcso) {
  fill: currentColor;
  d: path("M7 3.75a.75.75 0 0 0-1.5 0V9.5a4.5 4.5 0 1 0 9 0V3.75a.75.75 0 0 0-1.5 0V9.5a3 3 0 1 1-6 0zM5.75 15.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
