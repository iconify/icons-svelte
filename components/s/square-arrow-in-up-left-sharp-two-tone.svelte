<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wvzbsvdug"/><path class="k7ejdbcuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-in-up-left-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k7ejdbcuv) {
  d: path("M21.2929 21.2929L13.1464 13.1464M22 13L13 13L13 22");
}

:global(.wvzbsvdug) {
  stroke-opacity: 0.4;
  d: path("M10 17L3 17L3 3L17 3L17 10");
}

</style>
