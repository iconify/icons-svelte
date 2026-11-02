<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucmn5_ber"/><path class="bgbshn1il"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-right-bulk" {...props}></Icon>
<style>
:global(.bgbshn1il) {
  d: path("M3 7h18a1 1 0 0 1 0 2h-5v11a1 1 0 0 1-2 0V9H3a1 1 0 0 1 0-2");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ucmn5_ber) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 21a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3Z");
}

</style>
