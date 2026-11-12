<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="dqa_u8b9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:touchpad-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dqa_u8b9n) {
  d: path("M12 13h9a1 1 0 0 1 0 2h-8v4a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2Z");
}

:global(.n3ea6gw5u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

</style>
