<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mtet-5-cd"/><path class="zbgqcxb7p"/><path class="ntzm30buc"/><path class="on4ig8t5d"/><path class="smyhnv9tm"/><path class="ydl8e0r_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:union-duotone-bold" {...props}></Icon>
<style>
:global(.mtet-5-cd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ntzm30buc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.on4ig8t5d) {
  d: path("M5 4v10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.smyhnv9tm) {
  d: path("M19 14a7 7 0 0 1 -14 0");
}

:global(.ydl8e0r_x) {
  d: path("M19 4v10");
}

:global(.zbgqcxb7p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 14a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
