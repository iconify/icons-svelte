<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlvjbec6l"/><path class="nv98h9b6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:touchscreen" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nlvjbec6l) {
  d: path("M7.5 15.5H5A2.5 2.5 0 0 1 2.5 13V5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v7.5");
}

:global(.nv98h9b6s) {
  d: path("M10.5 21.5V10a1.5 1.5 0 0 1 3 0v4.5l3.5.75A1.5 1.5 0 0 1 18.25 17l-.5 4.5M8.536 8a4 4 0 0 1 6.928 0");
}

</style>
