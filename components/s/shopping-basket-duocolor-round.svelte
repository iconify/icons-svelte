<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uyl8pnj4k"/><path class="yr04eqofp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-basket-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uyl8pnj4k) {
  stroke-opacity: 0.4;
  d: path("m5 10l4-6m10 6l-4-6");
}

:global(.yr04eqofp) {
  d: path("M3 10h18M4 10l2 7c.507 1.776 1.732 3 3 3h6c1.268 0 2.493-1.224 3-3l2-7m-10 0v10m4-10v10");
}

</style>
