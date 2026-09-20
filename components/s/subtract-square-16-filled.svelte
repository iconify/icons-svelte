<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ehxsnn_eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:subtract-square-16-filled" {...props}></Icon>
<style>
:global(.ehxsnn_eh) {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zm3.5 3a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
