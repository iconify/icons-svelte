<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s63e1easn"/><path class="jxnokqx1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tab-pin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jxnokqx1t) {
  d: path("M11.5 7h1A1.5 1.5 0 0 1 14 8.5v1.546a1.5 1.5 0 0 0 .252.832L15 12a.965.965 0 0 1-.803 1.5H9.803A.965.965 0 0 1 9 12l.748-1.122a1.5 1.5 0 0 0 .252-.832V8.5A1.5 1.5 0 0 1 11.5 7m.5 6.5v5");
}

:global(.s63e1easn) {
  d: path("M2.5 19.5h2V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v13.5h2");
}

</style>
