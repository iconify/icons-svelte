<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qerbupbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-rectangle" {...props}></Icon>
<style>
:global(.qerbupbry) {
  fill: currentColor;
  d: path("M2 4h20v16H2z");
}

</style>
