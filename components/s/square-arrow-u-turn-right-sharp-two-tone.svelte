<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="peryhoawc"/><path class="x-_5ilohg"/><path class="v7fs5fzgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-u-turn-right-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.peryhoawc) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22L21 22C21.5523 22 22 21.5523 22 21L22 3C22 2.4477 21.5523 2 21 2L3 2Z");
  stroke: none;
}

:global(.v7fs5fzgi) {
  d: path("M15.9167 10.5L11.0797 10.5C9.3788 10.5 8 11.8431 8 13.5C8 15.1569 9.3788 16.5 11.0797 16.5L13.1063 16.5M12.8375 7.1909L16 10.5L12.8375 13.8091");
}

:global(.x-_5ilohg) {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>
