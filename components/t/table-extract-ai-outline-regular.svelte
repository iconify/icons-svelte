<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o72p0hsyz"/><path class="v9il_wb-q"/><path class="dznv025mt"/><path class="w_jkatblo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-extract-ai-outline-regular" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o72p0hsyz) {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

:global(.v9il_wb-q) {
  d: path("M6 10h12");
}

:global(.w_jkatblo) {
  d: path("M12 7v10");
}

</style>
