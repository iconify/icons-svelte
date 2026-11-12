<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3f_cjbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-warning-corner-fill-round" {...props}></Icon>
<style>
:global(.v3f_cjbui) {
  fill: currentColor;
  d: path("M21 9H4v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 8a1 1 0 0 1-1 1m-3 9a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-1 2h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
