<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ff9pr3oyh"/><path class="ulo4e4w4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stepper-duotone-sharp" {...props}></Icon>
<style>
:global(.ff9pr3oyh) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h18v8H3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ulo4e4w4v) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v8H3Zm4 4h10M3 18h6m6 0h6m-3-3v6");
}

</style>
