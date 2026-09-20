<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wdg881i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-3-bar-outline" {...props}></Icon>
<style>
:global(.z2wdg881i) {
  fill: currentColor;
  d: path("M3 21L21 3v18zm11.289-1H20V5.427l-5.712 5.712z");
}

</style>
