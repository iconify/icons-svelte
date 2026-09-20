<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sq37jvb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-indent-increase-ltr-16-filled" {...props}></Icon>
<style>
:global(.sq37jvb1z) {
  fill: currentColor;
  d: path("M5.75 3a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM2.28 5.72a.75.75 0 0 0-1.06 1.06l.97.97l-.97.97a.75.75 0 0 0 1.06 1.06l1.5-1.5a.75.75 0 0 0 0-1.06z");
}

</style>
