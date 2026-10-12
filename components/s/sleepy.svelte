<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="k-uix-ndb"/><circle class="i6a05acrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sleepy" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6a05acrm) {
  cx: 13.5px;
  cy: 14px;
  r: 1.5px;
}

:global(.k-uix-ndb) {
  d: path("M7.75 10c.75.75 2 .75 2.75 0m3 0c.75.75 2 .75 2.75 0m-6.5 8l3-.5");
}

</style>
