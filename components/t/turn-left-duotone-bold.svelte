<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qrhk1ib7b"/><path class="a8qb8pb7w"/><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-left-duotone-bold" {...props}></Icon>
<style>
:global(.a-wplf-uj) {
  d: path("M16 21V9H7");
}

:global(.a8qb8pb7w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 6 7 9l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrhk1ib7b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 21V9H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wd2ghz3oy) {
  d: path("M10 6 7 9l3 3");
}

</style>
