<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rp0qbo7xr"/><path class="m23phibpn"/><path class="g5nm6yyig"/><path class="ok9lcdcuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toll-booth-outline-thin" {...props}></Icon>
<style>
:global(.g5nm6yyig) {
  d: path("M20 12v9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m23phibpn) {
  d: path("M9 12h13");
}

:global(.ok9lcdcuh) {
  d: path("M17 21h5");
}

:global(.rp0qbo7xr) {
  d: path("M3 21V8l3 -3 3 3v13Z");
}

</style>
