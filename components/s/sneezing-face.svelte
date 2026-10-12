<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="k3q37cbyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sneezing-face" {...props}></Icon>
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

:global(.k3q37cbyn) {
  d: path("M7.5 8.5L10 9.75L7.5 11m9-2.5L14 9.75L16.5 11M10 13.5h4q1 0 1.66.75l.43.5q.66.75 0 1.5l-.43.5q-.66.75-1.66.75h-4q-1 0-1.66-.75l-.43-.5q-.66-.75 0-1.5l.43-.5Q9 13.5 10 13.5");
}

</style>
