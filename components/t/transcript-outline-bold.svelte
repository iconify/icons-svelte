<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="strt8mboj"/><path class="serb2umws"/><path class="r_4k1sbsg"/><path class="idjxm9bid"/><path class="d-_u6mtyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transcript-outline-bold" {...props}></Icon>
<style>
:global(.d-_u6mtyl) {
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.idjxm9bid) {
  d: path("M15 13h3");
}

:global(.r_4k1sbsg) {
  d: path("M7 13h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.serb2umws) {
  d: path("M15 8h3");
}

:global(.strt8mboj) {
  d: path("M7 8h6");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
