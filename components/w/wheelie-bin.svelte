<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vm1cy1wkc"/><path class="rw1ue1but"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wheelie-bin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rw1ue1but) {
  d: path("M7 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.vm1cy1wkc) {
  d: path("M5.5 7.5h13l-1 10.5h-11Zm14 0L5 3.5");
}

</style>
