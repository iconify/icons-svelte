<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yhw9facdq"/><path class="au8y-zggj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tampons-box" {...props}></Icon>
<style>
:global(.au8y-zggj) {
  d: path("M10.5 6.5a1.5 1.5 0 0 0 3 0m-4 5h5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 14.5 17h-5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 9.5 11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yhw9facdq) {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875V5.125A2.625 2.625 0 0 1 7.625 2.5M5 6.5h14");
}

</style>
