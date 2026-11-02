<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnq26wo8j"/><path class="sd3hecchs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qnq26wo8j) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21");
}

:global(.sd3hecchs) {
  d: path("M3 7h18a1 1 0 0 1 0 2H10v11a1 1 0 0 1-2 0V9H3a1 1 0 0 1 0-2");
}

</style>
