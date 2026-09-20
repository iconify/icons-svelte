<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="famncybwn"/><path class="rlkjycbtw"/><path class="du_3_4tit"/><path class="rvwqxxbhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:significance-test-outline-bold" {...props}></Icon>
<style>
:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.famncybwn) {
  d: path("M7 8v11");
}

:global(.rlkjycbtw) {
  d: path("M17 12v7");
}

:global(.rvwqxxbhr) {
  d: path("m9.5 4.5 2 2L15 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
