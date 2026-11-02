<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e6oegmu2x"/><path class="zyjmsnb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-duotone-sharp" {...props}></Icon>
<style>
:global(.e6oegmu2x) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 7h15a.998.998 0 0 1 .97 1.243l-2 8A1 1 0 0 1 19 17H8a1 1 0 0 1-.97-.757l-2-8A.998.998 0 0 1 6 7");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.zyjmsnb2r) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h2l3 12h11l2-8H6m2 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
