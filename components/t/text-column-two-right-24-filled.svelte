<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6qm0mo4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-two-right-24-filled" {...props}></Icon>
<style>
:global(.j6qm0mo4j) {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m13 0a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1M3 10a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m13 0a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1M3 14a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m13 0a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1M3 18a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m13 0a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

</style>
