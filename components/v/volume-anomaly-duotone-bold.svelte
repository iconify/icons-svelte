<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vapenum_d"/><path class="n8bikgk4k"/><path class="bnrswibpp"/><path class="yrlo_ib4h"/><path class="ets_btblg"/><path class="d5b4fcc2f"/><path class="vezho9b5g"/><path class="ul-6megvv"/><path class="hb39b-bug"/><path class="lqktbo2ou"/><path class="ejc7sbawl"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volume-anomaly-duotone-bold" {...props}></Icon>
<style>
:global(.bnrswibpp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ejc7sbawl) {
  d: path("M20 15v4");
}

:global(.ets_btblg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hb39b-bug) {
  d: path("M12 3v16");
}

:global(.lqktbo2ou) {
  d: path("M16 12v7");
}

:global(.n8bikgk4k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ul-6megvv) {
  d: path("M8 11v8");
}

:global(.vapenum_d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vezho9b5g) {
  d: path("M4 14v5");
}

:global(.yrlo_ib4h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
