<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pxvhxcchz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:teardrop-bottom-right-48-filled" {...props}></Icon>
<style>
:global(.pxvhxcchz) {
  fill: currentColor;
  d: path("M4 24C4 12.954 12.954 4 24 4s20 8.954 20 20v15.75A4.25 4.25 0 0 1 39.75 44H24C12.954 44 4 35.046 4 24");
}

</style>
