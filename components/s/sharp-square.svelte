<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6vc83tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-square" {...props}></Icon>
<style>
:global(.dk6vc83tr) {
  fill: currentColor;
  d: path("M3 3h18v18H3z");
}

</style>
