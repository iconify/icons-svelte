<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s_yqr1byx"/><path class="rvuhee-_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spell-check-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.rvuhee-_i) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6-3v6m4-8v8m0-3a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-1 8l3 3l6-6");
}

:global(.s_yqr1byx) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 12a3 3 0 1 1 0-6a3 3 0 0 1 0 6m10 0a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

</style>
