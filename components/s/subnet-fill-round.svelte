<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnmwlkbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:subnet-fill-round" {...props}></Icon>
<style>
:global(.qnmwlkbzp) {
  fill: currentColor;
  d: path("M13 7.829V10h4a5 5 0 0 1 5 5v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-2a5 5 0 0 1 5-5h4V7.829a3 3 0 1 1 2 0M7 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
