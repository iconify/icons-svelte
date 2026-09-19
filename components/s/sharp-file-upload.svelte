<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9nlzxm0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-file-upload" {...props}></Icon>
<style>
:global(.n9nlzxm0z) {
  fill: currentColor;
  d: path("M5 10h4v6h6v-6h4l-7-7zm0 8v2h14v-2z");
}

</style>
