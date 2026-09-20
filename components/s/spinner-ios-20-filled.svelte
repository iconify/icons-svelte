<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ndh18i1yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:spinner-ios-20-filled" {...props}></Icon>
<style>
:global(.ndh18i1yt) {
  fill: currentColor;
  d: path("M10 3.5A6.5 6.5 0 0 0 3.5 10A.75.75 0 0 1 2 10a8 8 0 1 1 8 8a.75.75 0 0 1 0-1.5a6.5 6.5 0 1 0 0-13");
}

</style>
