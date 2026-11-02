<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vtrnfhbfb"/><path class="mi0ekbbuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sofa-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mi0ekbbuq) {
  d: path("M4 5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V6h-5v7a1 1 0 0 1-2 0V6H6v3a1 1 0 0 1-2 0Zm2 14a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm14 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

:global(.vtrnfhbfb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 1 1 6 0v1h8v-1a3 3 0 1 1 6 0v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
