<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e32-qo9ho"/><path class="of79f_bgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trombone" {...props}></Icon>
<style>
:global(.e32-qo9ho) {
  d: path("m3.62 4.25l3.51 2Q8 6.75 8 7.5t-.87 1.25l-3.51 2q-.87.5-.87-.5v-5.5q0-1 .87-.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.of79f_bgi) {
  d: path("M8 7.5h11.25a2 2 0 0 1 2 2V15H8.5a2.75 2.75 0 0 0 0 5.5h12.75");
}

</style>
