<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj4rr7n5y"/><path class="zuzo0ubps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-battery-0-bar" {...props}></Icon>
<style>
:global(.qj4rr7n5y) {
  fill: currentColor;
  d: path("M9 6h6v14H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.zuzo0ubps) {
  fill: currentColor;
  d: path("M17 5v16c0 .55-.45 1-1 1H8c-.55 0-1-.45-1-1V5c0-.55.45-1 1-1h2V2h4v2h2c.55 0 1 .45 1 1m-2 1H9v14h6z");
}

</style>
