<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzm42kydi"/><path class="b58isb55w"/><path class="vrecxx6kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spade-outline-thin" {...props}></Icon>
<style>
:global(.b58isb55w) {
  d: path("M12 6v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vrecxx6kh) {
  d: path("M9 6h6");
}

:global(.xzm42kydi) {
  d: path("M8 13h8v4l-4 4 -4 -4Z");
}

</style>
