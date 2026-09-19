<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n34i-3bkw"/><path class="zpzkioj3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-bookmarks" {...props}></Icon>
<style>
:global(.n34i-3bkw) {
  fill: currentColor;
  d: path("M19 1H8.99C7.89 1 7 1.9 7 3h10c1.1 0 2 .9 2 2v13l2 1V3c0-1.1-.9-2-2-2m-4 4H5c-1.1 0-2 .9-2 2v16l7-3l7 3V7c0-1.1-.9-2-2-2m0 14.97l-4.21-1.81l-.79-.34l-.79.34L5 19.97V7h10z");
}

:global(.zpzkioj3d) {
  fill: currentColor;
  d: path("m5 19.97l5-2.15l5 2.15V7H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
