<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fsijhq84z"/><path class="xzm42kydi"/><path class="b58isb55w"/><path class="vrecxx6kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spade-duotone-bold" {...props}></Icon>
<style>
:global(.b58isb55w) {
  d: path("M12 6v7");
}

:global(.fsijhq84z) {
  fill: currentColor;
  d: path("M8 13h8v4l-4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vrecxx6kh) {
  d: path("M9 6h6");
}

:global(.xzm42kydi) {
  d: path("M8 13h8v4l-4 4 -4 -4Z");
}

</style>
