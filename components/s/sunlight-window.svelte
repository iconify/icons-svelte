<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vjl6jhbhk"/><path class="ot91t0b9z"/><path class="b4e05pbbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sunlight-window" {...props}></Icon>
<style>
:global(.b4e05pbbe) {
  d: path("m9.25 14.75l-4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ot91t0b9z) {
  fill: currentColor;
  d: path("M14.75 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.vjl6jhbhk) {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18V6A3.5 3.5 0 0 1 6 2.5m6 0v19M2.5 12h19");
}

</style>
