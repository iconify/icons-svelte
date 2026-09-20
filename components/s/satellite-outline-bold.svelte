<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b4-wc0yut"/><path class="k2kn5zbik"/><path class="omg7adb5g"/><path class="c60esnb_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:satellite-outline-bold" {...props}></Icon>
<style>
:global(.b4-wc0yut) {
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
}

:global(.c60esnb_c) {
  d: path("M6 20h10");
}

:global(.k2kn5zbik) {
  d: path("m11 13 6 -6");
}

:global(.omg7adb5g) {
  d: path("M11 13v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
