<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pfcz3bbdh"/><path class="jw8we0l5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:webcam-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jw8we0l5a) {
  d: path("M168 104a40 40 0 1 0-40 40a40 40 0 0 0 40-40m-64 0a24 24 0 1 1 24 24a24 24 0 0 1-24-24m120 96h-88v-16.4a80 80 0 1 0-16 0V200H32a8 8 0 0 0 0 16h192a8 8 0 0 0 0-16M64 104a64 64 0 1 1 64 64a64.07 64.07 0 0 1-64-64");
}

:global(.pfcz3bbdh) {
  d: path("M128 32a72 72 0 1 0 72 72a72 72 0 0 0-72-72m0 104a32 32 0 1 1 32-32a32 32 0 0 1-32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
