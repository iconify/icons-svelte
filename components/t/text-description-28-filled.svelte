<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="nif6tdbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-description-28-filled" {...props}></Icon>
<style>
:global(.nif6tdbtb) {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 0 0 2h21.997a1 1 0 1 0 0-2zm0 15a1 1 0 1 0 0 2h14.997a1 1 0 1 0 0-2zm-1-9a1 1 0 0 1 1-1h21.997a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1 4a1 1 0 1 0 0 2h21.997a1 1 0 1 0 0-2z");
}

</style>
