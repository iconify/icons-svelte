<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mha4wfbix"/><path class="pfpu_3ppl"/><path class="vwugbvz1g"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tax-paid-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mha4wfbix) {
  d: path("M9 3h6v5H9Z");
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.vwugbvz1g) {
  d: path("M4 12h16v5H4Z");
}

</style>
