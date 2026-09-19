<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsmy3kdku"/><path class="tbjwj-d5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-60" {...props}></Icon>
<style>
:global(.hsmy3kdku) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v7h10z");
}

:global(.tbjwj-d5q) {
  fill: currentColor;
  d: path("M7 11v11h10V11z");
}

</style>
