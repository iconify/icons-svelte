<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bucddhbte"/><path class="h_xkaqy0p"/><path class="cqw6oyk8z"/><path class="zwzgjsm-o"/><path class="s_3njwb9k"/><path class="sxnipqb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:traffic-jam-duotone-thin" {...props}></Icon>
<style>
:global(.bucddhbte) {
  fill: currentColor;
  d: path("M7.5 5.5 10 3h4l2.5 2.5V8h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cqw6oyk8z) {
  d: path("M3.5 2v20");
}

:global(.h_xkaqy0p) {
  fill: currentColor;
  d: path("M7.5 15.5 10 13h4l2.5 2.5V18h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_3njwb9k) {
  d: path("M7.5 5.5 10 3h4l2.5 2.5V8h-9Z");
}

:global(.sxnipqb0a) {
  d: path("M7.5 15.5 10 13h4l2.5 2.5V18h-9Z");
}

:global(.zwzgjsm-o) {
  d: path("M20.5 2v20");
}

</style>
