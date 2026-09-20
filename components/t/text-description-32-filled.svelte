<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pb6hw_f5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-description-32-filled" {...props}></Icon>
<style>
:global(.pb6hw_f5p) {
  fill: currentColor;
  d: path("M3.25 6a1.25 1.25 0 1 0 0 2.5h25.5a1.25 1.25 0 1 0 0-2.5zm0 6a1.25 1.25 0 1 0 0 2.5h25.5a1.25 1.25 0 1 0 0-2.5zM2 19.25c0-.69.56-1.25 1.25-1.25h25.5a1.25 1.25 0 1 1 0 2.5H3.25c-.69 0-1.25-.56-1.25-1.25M3.25 24a1.25 1.25 0 1 0 0 2.5h16.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
