<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="miy6bfbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-16-filled" {...props}></Icon>
<style>
:global(.miy6bfbkx) {
  fill: currentColor;
  d: path("M6.687 1.777a1.5 1.5 0 0 1 2.629 0l5.499 9.999a1.5 1.5 0 0 1-1.314 2.223H2.502a1.5 1.5 0 0 1-1.314-2.223z");
}

</style>
