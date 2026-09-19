<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj9lmobkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-clear-all" {...props}></Icon>
<style>
:global(.bj9lmobkz) {
  fill: currentColor;
  d: path("M5 11h14v2H5zm-2 4h14v2H3zm4-8h14v2H7z");
}

</style>
