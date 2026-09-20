<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="hz477cbpi"/><path class="sw8cph7mb"/><path class="lav0a10nn"/><path class="ppugtiwnu"/><path class="mg7aqnbsf"/><path class="mlhk78k2d"/><path class="l0v-b4kbr"/><path class="wy2n5sbyh"/><path class="b__1sjw6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tornado-duotone-regular" {...props}></Icon>
<style>
:global(.b__1sjw6v) {
  d: path("m11 18 2 2");
}

:global(.hz477cbpi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.lav0a10nn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.mlhk78k2d) {
  d: path("M5 8h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ppugtiwnu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11 18 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sw8cph7mb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy2n5sbyh) {
  d: path("M10 16h4");
}

</style>
