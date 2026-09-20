<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kuk8yacoy"/><path class="n8h0kccut"/><path class="if5ft31dv"/><path class="mdci-mi7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:topic-outline-bold" {...props}></Icon>
<style>
:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kuk8yacoy) {
  d: path("M8 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.mdci-mi7f) {
  d: path("M18 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n8h0kccut) {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
