<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqxu3wrxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-minus-corner-fill" {...props}></Icon>
<style>
:global(.dqxu3wrxg) {
  fill: currentColor;
  d: path("M11 8H3V6a3 3 0 0 1 3-3h5Zm2 0V3h5a3 3 0 0 1 3 3v2ZM3 14v-4h7v4Zm10 1h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m-3 1v4a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-2Z");
}

</style>
