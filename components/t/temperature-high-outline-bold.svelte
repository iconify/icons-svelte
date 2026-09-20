<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="le4-j1b7w"/><path class="rxj7i8-nj"/><path class="zbaxlgfvt"/><path class="j3gg_lb4w"/><path class="lkvhsog-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:temperature-high-outline-bold" {...props}></Icon>
<style>
:global(.j3gg_lb4w) {
  d: path("M16.5 6H19");
}

:global(.le4-j1b7w) {
  d: path("M9 6a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

:global(.lkvhsog-e) {
  d: path("M16.5 10H19");
}

:global(.rxj7i8-nj) {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zbaxlgfvt) {
  d: path("M12 6v8.5");
}

</style>
