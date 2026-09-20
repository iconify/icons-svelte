<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zmm0wsb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:teardrop-bottom-right-16-filled" {...props}></Icon>
<style>
:global(.zmm0wsb8k) {
  fill: currentColor;
  d: path("M1 8a7 7 0 0 1 14 0v5.25A1.75 1.75 0 0 1 13.25 15H8a7 7 0 0 1-7-7");
}

</style>
