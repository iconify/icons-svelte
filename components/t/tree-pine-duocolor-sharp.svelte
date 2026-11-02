<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oe7_vcbri"/><path class="j0ig87b_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-pine-duocolor-sharp" {...props}></Icon>
<style>
:global(.j0ig87b_y) {
  d: path("m12 3l5 4h-3l5 5h-4l6 6H3l6-6H5l5-5H7z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oe7_vcbri) {
  stroke-opacity: 0.4;
  d: path("M12 18v3");
}

</style>
