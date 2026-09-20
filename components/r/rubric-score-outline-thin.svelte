<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="qxdj2fbrx"/><path class="pdux64boo"/><path class="eqk2m_q5d"/><path class="cyrclk6ai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rubric-score-outline-thin" {...props}></Icon>
<style>
:global(.cyrclk6ai) {
  d: path("M14.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dx3ubrb9h) {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.eqk2m_q5d) {
  d: path("M9 15h4");
}

:global(.hbtmd5b0k) {
  d: path("M9.5 7V2.5h5V7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pdux64boo) {
  d: path("M14.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qxdj2fbrx) {
  d: path("M9 11h4");
}

</style>
