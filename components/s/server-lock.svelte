<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><rect class="xd_lnabfh"/><rect class="yc80kqblr"/><path class="qwn4--teq"/><path class="va-cqqbhp"/></g><rect class="rol6ayb1l"/><path class="gdbqatcys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:server-lock" {...props}></Icon>
<style>
:global(.gdbqatcys) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qwn4--teq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 7h.01m-.01 10h.01");
}

:global(.rol6ayb1l) {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.va-cqqbhp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7h5.5m-5.5 10h5.5");
}

:global(.xd_lnabfh) {
  width: 17.5px;
  height: 7.5px;
  x: 3.25px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yc80kqblr) {
  width: 17.5px;
  height: 7.5px;
  x: 3.25px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>
