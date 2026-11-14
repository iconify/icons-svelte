<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1093tfeo"/><path class="c-ve0_bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:support" {...props}></Icon>
<style>
:global(.c-ve0_bhz) {
  d: path("M6.25 20.5h8.5l6-4.5a1.5 1.5 0 0 0-2-2.25l-3.5 2.5M14 9.75c-1.75-1-3.5-2.5-3.5-4.5a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0c0 2-1.75 3.5-3.5 4.5");
}

:global(.g1093tfeo) {
  d: path("M3.5 12.75V21m2.75-7.5H9.5l3 2.25H14A1.125 1.125 0 0 1 14 18h-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
