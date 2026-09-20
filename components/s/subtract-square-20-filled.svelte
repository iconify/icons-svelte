<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt_7eabbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:subtract-square-20-filled" {...props}></Icon>
<style>
:global(.vt_7eabbe) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm.5 6.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1");
}

</style>
