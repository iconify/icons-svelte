<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu6d72pit"/><path class="h1vmt1quk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-folder-copy" {...props}></Icon>
<style>
:global(.h1vmt1quk) {
  fill: currentColor;
  d: path("M23 4h-9l-2-2H5.01L5 17h18z");
}

:global(.mu6d72pit) {
  fill: currentColor;
  d: path("M3 6H1v15h19v-2H3z");
}

</style>
