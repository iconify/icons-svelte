<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kaw7ibbdn"/><path class="pjz6otr4j"/><path class="fvlyeilkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sports-balls" {...props}></Icon>
<style>
:global(.fvlyeilkq) {
  d: path("M11.5 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M7 7.5h10M2.75 15Q7 16.5 6 21.25m10.5-4.75h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kaw7ibbdn) {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.pjz6otr4j) {
  d: path("M2.5 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
