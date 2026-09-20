<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw6xucujz"/><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="yqc0twwou"/><path class="y71fx-j7v"/><path class="tcu89np8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trade-order-duotone-thin" {...props}></Icon>
<style>
:global(.dx3ubrb9h) {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.hbtmd5b0k) {
  d: path("M9.5 7V2.5h5V7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iw6xucujz) {
  fill: currentColor;
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tcu89np8z) {
  d: path("m13.5 11 2.5 2.5 -2.5 2.5");
}

:global(.y71fx-j7v) {
  d: path("M10.5 11 8 13.5l2.5 2.5");
}

:global(.yqc0twwou) {
  d: path("M8 13.5h8");
}

</style>
