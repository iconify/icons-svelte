<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rxtmbxbvl"/><path class="k8ge4bcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:timer-check-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k8ge4bcec) {
  d: path("M10 2h4a1 1 0 0 1 0 2h-1v1a1 1 0 0 1-2 0V4h-1a1 1 0 0 1 0-2m7.293 4.293l2-2a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414-1.414m-6.36 8.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

:global(.rxtmbxbvl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9");
}

</style>
