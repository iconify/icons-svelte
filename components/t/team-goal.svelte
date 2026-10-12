<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_3shnbyh"/><circle class="w9x3n1bkv"/><path class="xa9rc3b0j"/><circle class="o3zsgvdcg"/><path class="lc4t_ebox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:team-goal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lc4t_ebox) {
  d: path("M15.5 21.25h5a.75.75 0 0 0 .75-.75c0-2.1-1.5-3.75-3.25-3.75s-3.25 1.65-3.25 3.75a.75.75 0 0 0 .75.75");
}

:global(.n_3shnbyh) {
  d: path("M12 3v10m0-10h6.25l-1.5 2l1.5 2H12Z");
}

:global(.o3zsgvdcg) {
  cx: 18px;
  cy: 13px;
  r: 2.25px;
}

:global(.w9x3n1bkv) {
  cx: 6px;
  cy: 13px;
  r: 2.25px;
}

:global(.xa9rc3b0j) {
  d: path("M3.5 21.25h5a.75.75 0 0 0 .75-.75c0-2.1-1.5-3.75-3.25-3.75S2.75 18.4 2.75 20.5a.75.75 0 0 0 .75.75");
}

</style>
