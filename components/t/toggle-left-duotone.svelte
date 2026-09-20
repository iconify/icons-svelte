<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e4y1m_rnv"/><path class="ckeg0lbyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:toggle-left-duotone" {...props}></Icon>
<style>
:global(.ckeg0lbyo) {
  d: path("M176 56H80a72 72 0 0 0 0 144h96a72 72 0 0 0 0-144m0 128H80a56 56 0 0 1 0-112h96a56 56 0 0 1 0 112M80 88a40 40 0 1 0 40 40a40 40 0 0 0-40-40m0 64a24 24 0 1 1 24-24a24 24 0 0 1-24 24");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e4y1m_rnv) {
  d: path("M112 128a32 32 0 1 1-32-32a32 32 0 0 1 32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
