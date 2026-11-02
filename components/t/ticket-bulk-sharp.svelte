<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bixu74c8y"/><path class="kq9dphvtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ticket-bulk-sharp" {...props}></Icon>
<style>
:global(.bixu74c8y) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kq9dphvtl) {
  d: path("M15 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
