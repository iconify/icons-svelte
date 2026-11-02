<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s0kf7kbuh"/><path class="fqs10vm1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wind-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fqs10vm1u) {
  d: path("M11 6a1 1 0 0 0 .922-1.387A.99.99 0 0 0 11 4a1 1 0 0 1 0-2a3 3 0 1 1 0 6H3a1 1 0 0 1 0-2Zm3 10a3 3 0 1 1 0 6a1 1 0 0 1 0-2a1.001 1.001 0 0 0 0-2H3a1 1 0 0 1 0-2Z");
}

:global(.s0kf7kbuh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 11a2 2 0 0 0 0-4a1 1 0 0 1 0-2a4 4 0 0 1 0 8H3a1 1 0 0 1 0-2Z");
}

</style>
