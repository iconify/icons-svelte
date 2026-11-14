<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jpsyv1blb"/><path class="lhiijub8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:travel-stolen-passport" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpsyv1blb) {
  d: path("M6 3h5a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 11 21H6a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 6 3");
}

:global(.lhiijub8e) {
  d: path("M5.75 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m-.25 6.5h6m6.5-1.75v3.5M18 21h.01");
}

</style>
