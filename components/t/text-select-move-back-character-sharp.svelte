<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv186187o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-select-move-back-character-sharp" {...props}></Icon>
<style>
:global(.iv186187o) {
  fill: currentColor;
  d: path("M11 5V3h2v2zm0 16v-2h2v2zM7 5V3h2v2zm0 16v-2h2v2zM3 5V3h2v2zm0 16v-2h2v2zm12 0v-2h2V5h-2V3h6v2h-2v14h2v2zm-8-5l-4-4l4-4l1.4 1.4L6.825 11H14v2H6.825L8.4 14.6z");
}

</style>
