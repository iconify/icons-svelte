<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mha4wfbix"/><path class="pfpu_3ppl"/><path class="vwugbvz1g"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tax-paid-outline-bold" {...props}></Icon>
<style>
:global(.mha4wfbix) {
  d: path("M9 3h6v5H9Z");
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.vwugbvz1g) {
  d: path("M4 12h16v5H4Z");
}

</style>
