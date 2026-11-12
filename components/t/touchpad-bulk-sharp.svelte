<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m2dtcxzwn"/><path class="dqa_u8b9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:touchpad-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dqa_u8b9n) {
  d: path("M12 13h9a1 1 0 0 1 0 2h-8v4a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2Z");
}

:global(.m2dtcxzwn) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

</style>
