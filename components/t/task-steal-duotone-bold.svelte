<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wpo12_pus"/><path class="cf6epupol"/><path class="riz4hpmhz"/><path class="os75_tbot"/><path class="rebfvp9ta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:task-steal-duotone-bold" {...props}></Icon>
<style>
:global(.cf6epupol) {
  d: path("M7.5 2.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.os75_tbot) {
  d: path("M8 12a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2");
}

:global(.rebfvp9ta) {
  d: path("m13 15 2 2");
}

:global(.riz4hpmhz) {
  d: path("M19.5 14.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wpo12_pus) {
  fill: currentColor;
  d: path("M8 12a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
