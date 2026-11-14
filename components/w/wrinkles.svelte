<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pii04_k8d"/><path class="f9esptb4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wrinkles" {...props}></Icon>
<style>
:global(.f9esptb4o) {
  d: path("M7 8q1.25-1.25 2.5 0T12 8t2.5 0T17 8M7 12q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0M7 16q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pii04_k8d) {
  d: path("M10.5 4h3a8 8 0 0 1 8 8a8 8 0 0 1-8 8h-3a8 8 0 0 1-8-8a8 8 0 0 1 8-8");
}

</style>
