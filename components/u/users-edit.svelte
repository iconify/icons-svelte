<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><circle class="y-aluxb2e"/><path class="l0cbzabqo"/></g><path class="uaginbcio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:users-edit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.l0cbzabqo) {
  d: path("M3.5 20.25h11a.75.75 0 0 0 .75-.75c0-2.9-2.7-5-6.25-5s-6.25 2.1-6.25 5a.75.75 0 0 0 .75.75M15 4.5a3.5 3.5 0 0 1 0 7m2.5 3.25c2.15.6 3.75 2.2 3.75 4.25v.5a.75.75 0 0 1-.75.75H19");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.uaginbcio) {
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

:global(.y-aluxb2e) {
  cx: 9px;
  cy: 8px;
  r: 3.5px;
}

</style>
