<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnrghp1vk"/><path class="o-4bk_b4n"/><path class="w6_tlja0w"/><path class="kpspt_bpo"/><path class="d2vyd9blc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-polo-duotone-bold" {...props}></Icon>
<style>
:global(.d2vyd9blc) {
  d: path("M3 18c3 -2 6 2 9 0s6 2 9 0");
}

:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w6_tlja0w) {
  d: path("M12 3v10");
}

:global(.xnrghp1vk) {
  fill: currentColor;
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
