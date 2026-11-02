<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zp76l5bgd"/><path class="b5_jfabhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ungroup-bulk-round" {...props}></Icon>
<style>
:global(.b5_jfabhs) {
  d: path("M17 13a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Zm-3 2a.997.997 0 0 0-1 1v1a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.zp76l5bgd) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 4h3a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3");
}

</style>
