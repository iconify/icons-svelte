<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="haomyccti"/><path class="x6e_qy8ax"/><path class="nwfxfzbpc"/><path class="zey5ebc0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tyre-duotone-bold" {...props}></Icon>
<style>
:global(.haomyccti) {
  fill: currentColor;
  d: path("M2 12a10 10 0 1 0 20 0 10 10 0 1 0 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nwfxfzbpc) {
  d: path("M2 12a10 10 0 1 0 20 0 10 10 0 1 0 -20 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x6e_qy8ax) {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
