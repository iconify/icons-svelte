<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="d4qr1ccbp"/><path class="rzfkscbuz"/><path class="rwz23pbvv"/><path class="oo4jx5bhi"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="sjot3p-qh"/><path class="aoxrbobxu"/><path class="qrln8gb_a"/><path class="ktpncgb0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:websocket-close-duotone-thin" {...props}></Icon>
<style>
:global(.aoxrbobxu) {
  d: path("M14 8h4");
}

:global(.d4qr1ccbp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ktpncgb0v) {
  d: path("M10 16H6");
}

:global(.oo4jx5bhi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qrln8gb_a) {
  d: path("M18 16h-4");
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rwz23pbvv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzfkscbuz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sjot3p-qh) {
  d: path("M6 8h4");
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
