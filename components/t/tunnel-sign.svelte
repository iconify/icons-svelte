<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a98uvfvvo"/><path class="lb0to798a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tunnel-sign" {...props}></Icon>
<style>
:global(.a98uvfvvo) {
  d: path("M2.5 21v-9a9.5 9.5 0 0 1 19 0v9M2 21h20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb0to798a) {
  d: path("M7 21v-6.5a5 5 0 0 1 10 0V21");
}

</style>
