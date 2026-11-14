<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rlqg5xb4a"/><path class="cl9t4obqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sla-met" {...props}></Icon>
<style>
:global(.cl9t4obqz) {
  d: path("m8 11.5l3.5 3.5l9-9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rlqg5xb4a) {
  d: path("M16.75 3.75a9.5 9.5 0 1 0 4.5 5.75");
}

</style>
