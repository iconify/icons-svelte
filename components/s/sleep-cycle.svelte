<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su75vcb-l"/><path class="f_a3m_bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sleep-cycle" {...props}></Icon>
<style>
:global(.f_a3m_bgc) {
  d: path("M21 6h-3v3m-4-.5a4.5 4.5 0 1 0 1.5 6.5A3.75 3.75 0 0 1 14 8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.su75vcb-l) {
  d: path("M12 3.5A8.5 8.5 0 1 0 18 6");
}

</style>
