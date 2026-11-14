<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg8nb-p7y"/><path class="pe9068s_v"/><path class="jtlp82emg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:time-series-db" {...props}></Icon>
<style>
:global(.fg8nb-p7y) {
  d: path("M3.5 3v17.5H12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtlp82emg) {
  d: path("M15 16v4a3.5 1.5 0 0 0 7 0v-4");
}

:global(.pe9068s_v) {
  d: path("m6.5 15.5l3.5-4l3 2l6.5-8M15 16a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0");
}

</style>
