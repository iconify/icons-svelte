<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_bxsbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-space-bar" {...props}></Icon>
<style>
:global(.mb_bxsbbi) {
  fill: currentColor;
  d: path("M18 13H6V9H4v6h16V9h-2z");
}

</style>
