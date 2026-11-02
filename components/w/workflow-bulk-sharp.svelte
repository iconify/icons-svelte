<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mc4chxb8t"/><path class="y9velvwdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:workflow-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mc4chxb8t) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm10 10a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1Z");
}

:global(.y9velvwdb) {
  d: path("M6 11a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2H7a1 1 0 0 1-1-1Z");
}

</style>
