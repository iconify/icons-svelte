<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y-0zbdc_n"/><path class="wg7q3_3dr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:whatsapp-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.wg7q3_3dr) {
  d: path("M10 10a4 4 0 0 0 4 4v-1a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1h-1a6 6 0 0 1-6-6V9a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2Z");
}

:global(.y-0zbdc_n) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.019 20.804l.935-4.673a9.945 9.945 0 1 1 4.915 4.915l-4.673.935a1 1 0 0 1-1.177-1.177");
}

</style>
