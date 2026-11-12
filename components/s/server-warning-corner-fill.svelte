<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znc4s2b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-warning-corner-fill" {...props}></Icon>
<style>
:global(.znc4s2b0f) {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M9 21H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m9-3a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m10 4a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
