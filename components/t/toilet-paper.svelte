<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m92fshsnx"/><path class="bdasx7b2q"/><circle class="ps6leydqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toilet-paper" {...props}></Icon>
<style>
:global(.bdasx7b2q) {
  d: path("M7.75 4.75a4.75 4.75 0 0 1 0 9.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m92fshsnx) {
  d: path("M7.75 4.75h9.5a2 2 0 0 1 2 2v14.5h-8v-7h-3.5a4.75 4.75 0 0 1 0-9.5");
}

:global(.ps6leydqj) {
  cx: 7.75px;
  cy: 9.5px;
  r: 1.5px;
}

</style>
