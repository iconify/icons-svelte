<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svhf6ebsk"/><path class="k9lru2b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-layers" {...props}></Icon>
<style>
:global(.k9lru2b0b) {
  fill: currentColor;
  d: path("m19.37 12.8l-7.38 5.74l-7.37-5.73L3 14.07l9 7l9-7zM12 2L3 9l1.63 1.27L12 16l7.36-5.73L21 9zm0 11.47L6.26 9L12 4.53L17.74 9z");
}

:global(.svhf6ebsk) {
  fill: currentColor;
  d: path("M6.26 9L12 13.47L17.74 9L12 4.53z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
