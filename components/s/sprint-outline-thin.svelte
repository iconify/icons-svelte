<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-xc2ibwn"/><path class="u46xm9b9w"/><path class="g6v1wdg_x"/><path class="q1ae0k4gd"/><path class="z91-mkbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sprint-outline-thin" {...props}></Icon>
<style>
:global(.a-xc2ibwn) {
  d: path("M12 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.g6v1wdg_x) {
  d: path("M10 12 6 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1ae0k4gd) {
  d: path("m14 16 4 4");
}

:global(.u46xm9b9w) {
  d: path("m14 8 -4 4 4 4");
}

:global(.z91-mkbau) {
  d: path("M3 20h5");
}

</style>
