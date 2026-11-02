<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adffvebhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallet-fill-sharp" {...props}></Icon>
<style>
:global(.adffvebhy) {
  fill: currentColor;
  d: path("M22 4v4h-7a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h7v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1m-6 10v-4h6v4Zm2-3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
