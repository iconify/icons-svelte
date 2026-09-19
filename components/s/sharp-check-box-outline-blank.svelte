<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewqsqbb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-check-box-outline-blank" {...props}></Icon>
<style>
:global(.ewqsqbb3w) {
  fill: currentColor;
  d: path("M19 5v14H5V5zm2-2H3v18h18z");
}

</style>
