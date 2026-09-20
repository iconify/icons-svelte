<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jrpnc2pnl"/><path class="hiqcqfbaf"/><path class="qye2ovraz"/><path class="elmoo_bpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:visual-diff-outline-thin" {...props}></Icon>
<style>
:global(.elmoo_bpw) {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hiqcqfbaf) {
  d: path("M12 8v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrpnc2pnl) {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.qye2ovraz) {
  d: path("M7 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
