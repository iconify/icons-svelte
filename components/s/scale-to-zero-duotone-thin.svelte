<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="j3zd1taaz"/><path class="qe97cg-lx"/><path class="f_0n8xbzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scale-to-zero-duotone-thin" {...props}></Icon>
<style>
:global(.e5rxwxb6q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f_0n8xbzv) {
  d: path("m5 7 6 6 8 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3zd1taaz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 7 6 6 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

</style>
