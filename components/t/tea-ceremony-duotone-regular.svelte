<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lq0ly8b8d"/><path class="gsvssdbyc"/><path class="v9yujbbpa"/><path class="lwcjgibmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tea-ceremony-duotone-regular" {...props}></Icon>
<style>
:global(.gsvssdbyc) {
  d: path("M5 12h12v4c0 3 -3 4 -6 4s-6 -1 -6 -4Z");
}

:global(.lq0ly8b8d) {
  fill: currentColor;
  d: path("M5 12h12v4c0 3 -3 4 -6 4s-6 -1 -6 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lwcjgibmo) {
  d: path("M7 12c0 -3 2 -5 4 -5s4 2 4 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v9yujbbpa) {
  d: path("m17 14 3 -3");
}

</style>
