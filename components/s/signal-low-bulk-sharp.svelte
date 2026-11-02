<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xlinu8bdl"/><path class="kgy_edcgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signal-low-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kgy_edcgj) {
  d: path("M11 12v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m-6 4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Z");
}

:global(.xlinu8bdl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.01 19a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
