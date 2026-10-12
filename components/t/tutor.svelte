<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vkh2p_buw"/><path class="y_f3o1p3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tutor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vkh2p_buw) {
  cx: 7.5px;
  cy: 7px;
  r: 2.75px;
}

:global(.y_f3o1p3c) {
  d: path("M3.75 21.25v-4.5a3.75 3.75 0 0 1 7.5 0v4.5Zm10.25-10c1.4-.6 2.6-.5 3.5.35c.9-.85 2.1-.95 3.5-.35v7c-1.4-.6-2.6-.5-3.5.35c-.9-.85-2.1-.95-3.5-.35Zm3.5.35v7");
}

</style>
