<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oe7_vcbri"/><path class="j737g8fpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-pine-duocolor" {...props}></Icon>
<style>
:global(.j737g8fpb) {
  d: path("m14 7l4 4c.369.369.369 1 0 1h-3l5 5c.369.369.369 1 0 1H4c-.369 0-.369-.631 0-1l5-5H6c-.369 0-.369-.631 0-1l4-4H7l5-4l5 4z");
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
