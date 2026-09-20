<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="mlhk78k2d"/><path class="l0v-b4kbr"/><path class="wy2n5sbyh"/><path class="b__1sjw6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tornado-outline-thin" {...props}></Icon>
<style>
:global(.b__1sjw6v) {
  d: path("m11 18 2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.mlhk78k2d) {
  d: path("M5 8h14");
}

:global(.wy2n5sbyh) {
  d: path("M10 16h4");
}

</style>
