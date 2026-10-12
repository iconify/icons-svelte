<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="elds3ilxm"/><circle class="sa8oq8bea"/><circle class="nmoouyb9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:team-tree" {...props}></Icon>
<style>
:global(.elds3ilxm) {
  d: path("M12 7.75V12m0 0l-4.59 4.59M12 12l4.59 4.59");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nmoouyb9r) {
  cx: 18px;
  cy: 18px;
  r: 2px;
}

:global(.sa8oq8bea) {
  cx: 6px;
  cy: 18px;
  r: 2px;
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
