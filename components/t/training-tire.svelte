<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_3sk0b3c"/><path class="kr4fvryln"/><path class="dpzllgllh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:training-tire" {...props}></Icon>
<style>
:global(.dpzllgllh) {
  d: path("M7.5 9.5a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kr4fvryln) {
  d: path("M3 9.5V14c0 2.5 4 4.5 9 4.5s9-2 9-4.5V9.5");
}

:global(.q_3sk0b3c) {
  d: path("M3 9.5a9 4.5 0 1 0 18 0a9 4.5 0 1 0-18 0");
}

</style>
