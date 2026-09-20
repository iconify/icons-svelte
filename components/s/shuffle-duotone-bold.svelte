<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v9hkdub2y"/><path class="bmpn0zqcr"/><path class="qcttaobtu"/><path class="hvc_kfbbh"/><path class="fipykcbwt"/><path class="d210vyb8t"/><path class="ig2rw3qjx"/><path class="hs_3awbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shuffle-duotone-bold" {...props}></Icon>
<style>
:global(.bmpn0zqcr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d210vyb8t) {
  d: path("m18 13 3 3 -3 3");
}

:global(.fipykcbwt) {
  d: path("M3 7h6l9 9h3");
}

:global(.hs_3awbse) {
  d: path("m18 5 3 3 -3 3");
}

:global(.hvc_kfbbh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ig2rw3qjx) {
  d: path("M3 17h6l9 -9h3");
}

:global(.qcttaobtu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h6l9 -9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v9hkdub2y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h6l9 9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
