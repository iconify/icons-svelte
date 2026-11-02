<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j_tc-w5gp"/><path class="em57w9skn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-off-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.em57w9skn) {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

:global(.j_tc-w5gp) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.414 6.172l2.879-2.879A1 1 0 0 1 15 4v6.757ZM7 7l8 8v5a1.002 1.002 0 0 1-1.707.707L9.586 17H6a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Z");
}

</style>
