<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpgwk1any"/><path class="enzss73yz"/><path class="mmsx_cc6e"/><path class="i9m3_0b4x"/><path class="mi_rhabsp"/><path class="pm0e7ny3b"/><path class="tbo01n9ke"/><path class="s88iiwf1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:villa-duotone-bold" {...props}></Icon>
<style>
:global(.enzss73yz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11v8h8v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hpgwk1any) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 11 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9m3_0b4x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 19 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mi_rhabsp) {
  d: path("m2 11 6 -6 6 6");
}

:global(.mmsx_cc6e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 14 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pm0e7ny3b) {
  d: path("M4 11v8h8v-8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s88iiwf1g) {
  d: path("m15 19 2 -2 2 2 2 -2");
}

:global(.tbo01n9ke) {
  d: path("m15 14 2 -2 2 2 2 -2");
}

</style>
