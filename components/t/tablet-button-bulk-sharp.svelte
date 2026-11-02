<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xg2nkqahl"/><path class="zenlmhbbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-button-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.xg2nkqahl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

:global(.zenlmhbbk) {
  d: path("M12 17h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
