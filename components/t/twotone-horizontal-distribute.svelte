<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwd3o3boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-horizontal-distribute" {...props}></Icon>
<style>
:global(.pwd3o3boq) {
  fill: currentColor;
  d: path("M4 22H2V2h2zM22 2h-2v20h2zm-8.5 5h-3v10h3z");
}

</style>
