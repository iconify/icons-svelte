<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pemn838wn"/><path class="ounpu_b6c"/><path class="vblqyfbsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sculpture-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ounpu_b6c) {
  d: path("M7 13a5 5 0 0 1 10 0");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vblqyfbsp) {
  d: path("M7 16h10v4H7Z");
}

</style>
