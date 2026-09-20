<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kt4jgwb2r"/><path class="j-70hcbzd"/><path class="j_72l_3ug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-shard-outline-bold" {...props}></Icon>
<style>
:global(.j_72l_3ug) {
  d: path("m17 8 4 4 -4 4Z");
}

:global(.j-70hcbzd) {
  d: path("m10 8 4 4 -4 4Z");
}

:global(.kt4jgwb2r) {
  d: path("m3 8 4 4 -4 4Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
