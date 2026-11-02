<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nhs610-0q"/><path class="xt3t0x6az"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:x-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nhs610-0q) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h4a1 1 0 0 1 .8.4l12 16A.999.999 0 0 1 20 21h-4a1 1 0 0 1-.8-.4l-12-16A.999.999 0 0 1 4 3");
}

:global(.xt3t0x6az) {
  d: path("m13.2 11.4l6-8a1 1 0 1 1 1.6 1.2l-6 8a1 1 0 0 1-1.6-1.2m-10 8l6-8a1 1 0 0 1 1.6 1.2l-6 8a1 1 0 0 1-1.6-1.2");
}

</style>
