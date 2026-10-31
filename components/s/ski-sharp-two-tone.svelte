<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gn9g1vely"/><path class="wfirp1jzk"/><path class="nnx5j0bae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ski-sharp-two-tone" {...props}></Icon>
<style>
:global(.gn9g1vely) {
  stroke-opacity: 0.4;
  d: path("M2.2093 16.8308L21.7907 21.0221");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nnx5j0bae) {
  fill: currentColor;
  d: path("M17 4C17 5.1046 16.1046 6 15 6C13.8954 6 13 5.1046 13 4C13 2.8954 13.8954 2 15 2C16.1046 2 17 2.8954 17 4Z");
  stroke: none;
}

:global(.wfirp1jzk) {
  d: path("M13.2929 8.7071L9 13L14 16L11 18.7124M12 10L16.5528 12.2764");
}

</style>
