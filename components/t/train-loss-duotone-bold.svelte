<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="g6jtd0b_d"/><path class="qe97cg-lx"/><path class="ea0o9gbbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:train-loss-duotone-bold" {...props}></Icon>
<style>
:global(.ea0o9gbbj) {
  d: path("m5 6 6 6 4 4h4");
}

:global(.g6jtd0b_d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 6 6 6 4 4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yxjvqtiry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
