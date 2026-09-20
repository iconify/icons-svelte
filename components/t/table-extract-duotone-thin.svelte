<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixb_9n80q"/><path class="qkvbmegyz"/><path class="r94rlzz7k"/><path class="mqtixbwqo"/><path class="g9ieqkjwc"/><path class="l2x_qk6ul"/><path class="v6z04rqrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-extract-duotone-thin" {...props}></Icon>
<style>
:global(.g9ieqkjwc) {
  d: path("M9 8v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixb_9n80q) {
  fill: currentColor;
  d: path("M14 3h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l2x_qk6ul) {
  d: path("M15 8v7");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.qkvbmegyz) {
  fill: currentColor;
  d: path("M6 20a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r94rlzz7k) {
  d: path("M14 3h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3h5");
}

:global(.v6z04rqrf) {
  d: path("M6 20a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2");
}

</style>
