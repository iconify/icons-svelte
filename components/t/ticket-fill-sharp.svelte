<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-yoa164u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ticket-fill-sharp" {...props}></Icon>
<style>
:global(.t-yoa164u) {
  fill: currentColor;
  d: path("M13 19H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h10Zm2 0V5h6a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1Z");
}

</style>
