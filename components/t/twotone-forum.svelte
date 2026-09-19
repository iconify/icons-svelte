<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d14512rpr"/><path class="viux_sbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-forum" {...props}></Icon>
<style>
:global(.d14512rpr) {
  fill: currentColor;
  d: path("M15 11V4H4v8.17L5.17 11H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.viux_sbct) {
  fill: currentColor;
  d: path("M16 13c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v14l4-4zm-12-.83V4h11v7H5.17zM22 7c0-.55-.45-1-1-1h-2v9H6v2c0 .55.45 1 1 1h11l4 4z");
}

</style>
