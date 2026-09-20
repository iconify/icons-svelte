<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r4it7dimk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:window-32-filled" {...props}></Icon>
<style>
:global(.r4it7dimk) {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zm2 17A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5V11H5z");
}

</style>
