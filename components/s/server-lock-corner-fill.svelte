<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czy1fj-es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-lock-corner-fill" {...props}></Icon>
<style>
:global(.czy1fj-es) {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 17a2 2 0 0 1 2-2a3 3 0 1 1 6 0a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm-3 4H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m7-6h2a1 1 0 0 0-2 0m-8.99 1H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M20 17h-6v3h6Z");
}

</style>
