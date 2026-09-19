<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cst0x0bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-file-copy" {...props}></Icon>
<style>
:global(.cst0x0bcx) {
  fill: currentColor;
  d: path("M16 1H2v16h2V3h12zm-1 4l6 6v12H6V5zm-1 7h5.5L14 6.5z");
}

</style>
