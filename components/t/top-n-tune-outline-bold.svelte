<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zrmtxyafv"/><path class="u07qp3bhr"/><path class="kiz2lrbtx"/><path class="y_or9-s0p"/><path class="yqy8x4bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-n-tune-outline-bold" {...props}></Icon>
<style>
:global(.kiz2lrbtx) {
  d: path("M8 14h12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u07qp3bhr) {
  d: path("M8 9h12");
}

:global(.y_or9-s0p) {
  d: path("M8 19h12");
}

:global(.yqy8x4bvc) {
  d: path("M5.5 2H3v9h2.5");
}

:global(.zrmtxyafv) {
  d: path("M8 4h12");
}

</style>
