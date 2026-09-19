<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zev-vkbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-timer-3-select" {...props}></Icon>
<style>
:global(.zev-vkbqo) {
  fill: currentColor;
  d: path("M21 11v2h-4v1h4v5h-6v-2h4v-1h-4v-5zM4 5v3h6v2.5H4v3h6V16H4v3h9V5z");
}

</style>
