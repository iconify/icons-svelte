<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0umfpbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-select-jump-to-beginning-outline" {...props}></Icon>
<style>
:global(.p0umfpbml) {
  fill: currentColor;
  d: path("M19 5V3h2v2zm0 16v-2h2v2zM15 5V3h2v2zm0 16v-2h2v2zM11 5V3h2v2zM7 5V3h2v2zm0 16v-2h2v2zm-4 0V3h2v18zm11-5l-4-4l4-4l1.4 1.4l-1.575 1.6H21v2h-7.175l1.575 1.6zm-3 5v-2h2v2z");
}

</style>
