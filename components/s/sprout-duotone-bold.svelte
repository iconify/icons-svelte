<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nq5dvkfgq"/><path class="r02d1nb9l"/><path class="ricsl-blc"/><path class="uy3jp_bjh"/><path class="i30itkxpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sprout-duotone-bold" {...props}></Icon>
<style>
:global(.i30itkxpw) {
  d: path("M12.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

:global(.nq5dvkfgq) {
  fill: currentColor;
  d: path("M3.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r02d1nb9l) {
  fill: currentColor;
  d: path("M12.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uy3jp_bjh) {
  d: path("M3.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

</style>
