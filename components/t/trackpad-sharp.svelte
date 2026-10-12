<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l7yfq-b6e"/><circle class="o6hs5du5w"/><path class="wcpvigl8r"/><path class="utuz09bqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trackpad-sharp" {...props}></Icon>
<style>
:global(.l7yfq-b6e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.o6hs5du5w) {
  cx: 12px;
  cy: 10px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utuz09bqr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16h18.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wcpvigl8r) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10h.01");
}

</style>
