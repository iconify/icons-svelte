<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw_mod-bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-notes" {...props}></Icon>
<style>
:global(.gw_mod-bn) {
  fill: currentColor;
  d: path("M21 11.01L3 11v2h18zM3 16h12v2H3zM21 6H3v2.01L21 8z");
}

</style>
