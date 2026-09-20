<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h9brizbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-paragraph-direction-left-20-regular" {...props}></Icon>
<style>
:global(.h9brizbkd) {
  fill: currentColor;
  d: path("M11.5 3a4 4 0 1 0 0 8H13v6.5a.5.5 0 0 0 1 0V4h1v13.5a.5.5 0 0 0 1 0V4h.5a.5.5 0 0 0 0-1zM13 4v6h-1.5a3 3 0 0 1 0-6zM5.854 7.646a.5.5 0 0 0-.708 0l-2 2a.5.5 0 0 0 0 .708l2 2a.5.5 0 0 0 .708-.708L4.207 10l1.647-1.646a.5.5 0 0 0 0-.708");
}

</style>
