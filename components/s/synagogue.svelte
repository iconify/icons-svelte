<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkclsnbiv"/><path class="ujpzdibug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:synagogue" {...props}></Icon>
<style>
:global(.bkclsnbiv) {
  d: path("M2.75 21.25V7a2 2 0 0 1 4 0v4l4.7-4.25a.8.8 0 0 1 1.1 0l4.7 4.25V7a2 2 0 0 1 4 0v14.25Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ujpzdibug) {
  d: path("m12 9l2.17 3.75H9.83Zm0 5l2.17-3.75H9.83Zm-1.5 7.25v-2.5a1.5 1.5 0 0 1 3 0v2.5");
}

</style>
