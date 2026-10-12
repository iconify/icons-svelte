<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2nk7xbhz"/><circle class="en1zq61jm"/><path class="tg81c0bqt"/><circle class="zop88fbkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:steps-counter" {...props}></Icon>
<style>
:global(.en1zq61jm) {
  cx: 7.5px;
  cy: 17.25px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2nk7xbhz) {
  d: path("M7.5 2.75a3 4.75 0 1 1 0 9.5a3 4.75 0 1 1 0-9.5");
}

:global(.tg81c0bqt) {
  d: path("M16.5 4.75a3 4.75 0 1 1 0 9.5a3 4.75 0 1 1 0-9.5");
}

:global(.zop88fbkj) {
  cx: 16.5px;
  cy: 19.25px;
  r: 2px;
}

</style>
