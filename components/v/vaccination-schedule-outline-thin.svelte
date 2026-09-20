<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cu26jmb_i"/><path class="j835zw5-z"/><path class="q7kpryb3v"/><path class="a8cyhwbdj"/><path class="ksrxg1b4b"/><path class="uuj0dsv7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vaccination-schedule-outline-thin" {...props}></Icon>
<style>
:global(.a8cyhwbdj) {
  d: path("M16 2v3");
}

:global(.cu26jmb_i) {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.ksrxg1b4b) {
  d: path("m8 19 7 -7");
}

:global(.q7kpryb3v) {
  d: path("M8 2v3");
}

:global(.uuj0dsv7p) {
  d: path("m13 11 3 3");
}

</style>
