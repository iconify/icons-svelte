<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q95mx0efm"/><path class="vpa8bs10m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thermometer-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.q95mx0efm) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 11.423V5a3 3 0 1 1 6 0v6.423a5.473 5.473 0 1 1-6 0");
}

:global(.vpa8bs10m) {
  d: path("M19 3a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm-2 3a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm2 3a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
