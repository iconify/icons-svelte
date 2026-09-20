<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gsvssdbyc"/><path class="v9yujbbpa"/><path class="lwcjgibmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tea-ceremony-outline-bold" {...props}></Icon>
<style>
:global(.gsvssdbyc) {
  d: path("M5 12h12v4c0 3 -3 4 -6 4s-6 -1 -6 -4Z");
}

:global(.lwcjgibmo) {
  d: path("M7 12c0 -3 2 -5 4 -5s4 2 4 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v9yujbbpa) {
  d: path("m17 14 3 -3");
}

</style>
