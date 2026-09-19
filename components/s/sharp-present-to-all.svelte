<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2xc8bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-present-to-all" {...props}></Icon>
<style>
:global(.hi2xc8bop) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16.02H3V4.98h18zM10 12H8l4-4l4 4h-2v4h-4z");
}

</style>
