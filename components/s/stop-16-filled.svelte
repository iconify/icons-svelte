<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rrgw-ybbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:stop-16-filled" {...props}></Icon>
<style>
:global(.rrgw-ybbv) {
  fill: currentColor;
  d: path("M3.5 2A1.5 1.5 0 0 0 2 3.5v9A1.5 1.5 0 0 0 3.5 14h9a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 12.5 2z");
}

</style>
