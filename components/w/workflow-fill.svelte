<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4zl299kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:workflow-fill" {...props}></Icon>
<style>
:global(.u4zl299kq) {
  fill: currentColor;
  d: path("M4 2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8v3a1 1 0 0 0 1 1h3v-2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-2H9a3 3 0 0 1-3-3v-3H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2");
}

</style>
