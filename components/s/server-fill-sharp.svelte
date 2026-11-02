<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qab42cb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-fill-sharp" {...props}></Icon>
<style>
:global(.qab42cb6h) {
  fill: currentColor;
  d: path("M3 3h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m4 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-4 7h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1m4 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
