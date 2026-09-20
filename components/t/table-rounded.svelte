<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqlviybsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:table-rounded" {...props}></Icon>
<style>
:global(.aqlviybsf) {
  fill: currentColor;
  d: path("M11 16H3v3q0 .825.588 1.413T5 21h6zm2 0v5h6q.825 0 1.413-.587T21 19v-3zm-2-2V9H3v5zm2 0h8V9h-8zM3 7h18V5q0-.825-.587-1.412T19 3H5q-.825 0-1.412.588T3 5z");
}

</style>
