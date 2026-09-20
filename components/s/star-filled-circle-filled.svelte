<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGSLF6QdjC"><path class="k5-vjlrin"/><path class="x0__bopre"/></mask></defs><circle mask="url(#SVGSLF6QdjC)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:star-filled-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.x0__bopre) {
  fill: var(--svg-color--000, #000);
  d: path("m13 18.97l-4.295 1.916a1 1 0 0 1-1.402-1.019l.494-4.677l-3.148-3.493a1 1 0 0 1 .535-1.647l4.6-.976L12.134 5a1 1 0 0 1 1.732 0l2.35 4.074l4.6.976a1 1 0 0 1 .535 1.647l-3.148 3.494l.494 4.676a1 1 0 0 1-1.402 1.018z");
}

</style>
