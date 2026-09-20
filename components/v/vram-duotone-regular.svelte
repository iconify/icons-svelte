<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fs7w_vboi"/><path class="a9xazx6hn"/><path class="dqfmwwbrv"/><path class="l517yxbln"/><path class="objyy5b5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vram-duotone-regular" {...props}></Icon>
<style>
:global(.a9xazx6hn) {
  d: path("M14 6h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3h5");
}

:global(.dqfmwwbrv) {
  d: path("M7 9v6");
}

:global(.fs7w_vboi) {
  fill: currentColor;
  d: path("M14 6h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.objyy5b5b) {
  d: path("M17 9v6");
}

</style>
