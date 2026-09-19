<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp3g3ccne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-1-bar" {...props}></Icon>
<style>
:global(.sp3g3ccne) {
  fill: currentColor;
  d: path("M17 4v18H7V4h3V2h4v2zm-2 2H9v12h6z");
}

</style>
