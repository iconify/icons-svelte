<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfgrg9zie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-24-filled" {...props}></Icon>
<style>
:global(.kfgrg9zie) {
  fill: currentColor;
  d: path("M5 6a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m4 12a1 1 0 0 1 1-1h11a1 1 0 1 1 0 2H10a1 1 0 0 1-1-1m-6-7a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>
