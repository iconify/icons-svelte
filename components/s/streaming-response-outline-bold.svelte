<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r43f98s5i"/><path class="b-11-accn"/><path class="z813dgbpy"/><path class="rxvgnomvg"/><path class="b5yjngbwf"/><path class="ql24hzbyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:streaming-response-outline-bold" {...props}></Icon>
<style>
:global(.b-11-accn) {
  d: path("M5 7h10");
}

:global(.b5yjngbwf) {
  d: path("M9.5 19H13");
}

:global(.ql24hzbyo) {
  d: path("M16 19h3.5");
}

:global(.r43f98s5i) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.rxvgnomvg) {
  d: path("M3 19h3.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z813dgbpy) {
  d: path("M5 11h5");
}

</style>
