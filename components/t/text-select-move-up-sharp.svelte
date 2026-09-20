<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7aqelbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-select-move-up-sharp" {...props}></Icon>
<style>
:global(.q7aqelbsu) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm8-4v-6.175L9.4 12.4L8 11l4-4l4 4l-1.4 1.4l-1.6-1.575V17zM3 5V3h18v2z");
}

</style>
