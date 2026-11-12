<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qv681sbkm"/><path class="l-2ji4zxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-lock-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.l-2ji4zxg) {
  d: path("M16 10v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1a3 3 0 1 1 6 0a1 1 0 0 1 1 1m-3-1a1 1 0 0 0-2 0Z");
}

:global(.qv681sbkm) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h16a1 1 0 0 1 1 1v7c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V3a1 1 0 0 1 1-1");
}

</style>
