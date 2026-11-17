<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tm8j1iuvr"/><path class="eu4z3fb8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:telescope-duotone-sharp" {...props}></Icon>
<style>
:global(.eu4z3fb8l) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 10l14-7l2 4l-14 7zm10-5l2 4m-4 2L7 21m5-10l5 10");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.tm8j1iuvr) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m18 3l2 4l-14 7l-2-4Z");
}

</style>
