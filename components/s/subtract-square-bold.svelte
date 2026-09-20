<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="otb-eqw5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subtract-square-bold" {...props}></Icon>
<style>
:global(.otb-eqw5r) {
  fill: currentColor;
  d: path("M228 160V96a12 12 0 0 0-12-12h-44V40a12 12 0 0 0-12-12H40a12 12 0 0 0-12 12v120a12 12 0 0 0 12 12h44v44a12 12 0 0 0 12 12h120a12 12 0 0 0 12-12zm-63 44l-32-32h22l32 32Zm7-49v-22l32 32v22Zm32-24l-23-23h23ZM52 52h96v96H52Zm56 129l23 23h-23Z");
}

</style>
