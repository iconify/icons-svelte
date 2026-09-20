<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="tootc1vfl"/><path class="hosrnl1cs"/><path class="ln0rvbbeo"/><path class="hocqw0ivk"/><path class="mg7aqnbsf"/><path class="mlhk78k2d"/><path class="l0v-b4kbr"/><path class="wy2n5sbyh"/><path class="b__1sjw6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tornado-duotone-thin" {...props}></Icon>
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

:global(.hocqw0ivk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 18 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hosrnl1cs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.ln0rvbbeo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.mlhk78k2d) {
  d: path("M5 8h14");
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tootc1vfl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy2n5sbyh) {
  d: path("M10 16h4");
}

</style>
