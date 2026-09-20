<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="axr5pmbgx"/><path class="up7vunb7t"/><path class="r7xk8o29f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:science-lens-duotone-bold" {...props}></Icon>
<style>
:global(.axr5pmbgx) {
  fill: currentColor;
  d: path("M4 12c4 -8 12 -8 16 0 -4 8 -12 8 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.up7vunb7t) {
  d: path("M4 12c4 -8 12 -8 16 0 -4 8 -12 8 -16 0");
}

</style>
