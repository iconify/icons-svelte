<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugh6y_a-z"/><path class="yf3jrcb6o"/><path class="mcubrkb2y"/><path class="znp96bc9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:swift-transfer-duotone-bold" {...props}></Icon>
<style>
:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ugh6y_a-z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yf3jrcb6o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 12 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znp96bc9s) {
  d: path("m15 12 -3 3h2.5l-3 3");
}

</style>
