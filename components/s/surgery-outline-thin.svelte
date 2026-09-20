<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgdt4_0wi"/><path class="s09hy0b0y"/><path class="c6uw-ccfl"/><path class="kkid9bb2e"/><path class="spncj1b6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surgery-outline-thin" {...props}></Icon>
<style>
:global(.c6uw-ccfl) {
  d: path("M7 14h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kkid9bb2e) {
  d: path("M5 14a3 3 0 0 1 0 -6");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.sgdt4_0wi) {
  d: path("M5 8h14v5a7 5 0 0 1 -14 0Z");
}

:global(.spncj1b6w) {
  d: path("M19 8a3 3 0 0 1 0 6");
}

</style>
