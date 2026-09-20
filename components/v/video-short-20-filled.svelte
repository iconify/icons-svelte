<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="saikndfvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:video-short-20-filled" {...props}></Icon>
<style>
:global(.saikndfvo) {
  fill: currentColor;
  d: path("M13.154 2.004A3 3 0 0 1 16 5v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6zm-3.64 5.64A1 1 0 0 0 8 8.502v2.996a1 1 0 0 0 1.514.858l2.504-1.498a1 1 0 0 0 0-1.716z");
}

</style>
