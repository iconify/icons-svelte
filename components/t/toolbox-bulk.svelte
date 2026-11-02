<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k6epo0b3t"/><path class="rkz5-t7ck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:toolbox-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k6epo0b3t) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

:global(.rkz5-t7ck) {
  d: path("M8 5a2 2 0 0 1 2-2h4.001A2 2 0 0 1 16 5v3a1 1 0 0 1-2 0V5h-4v3a1 1 0 0 1-2 0Zm-1 8v-1a1 1 0 0 1 2 0v1h6v-1a1 1 0 0 1 2 0v1h4a1 1 0 0 1 0 2h-4v1a1 1 0 0 1-2 0v-1H9v1a1 1 0 0 1-2 0v-1H3a1 1 0 0 1 0-2Z");
}

</style>
