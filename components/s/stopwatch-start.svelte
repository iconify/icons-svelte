<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrzqgdjzg"/><path class="njl_u6bdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stopwatch-start" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrzqgdjzg) {
  d: path("M4 13.25a8 8 0 1 0 16 0a8 8 0 1 0-16 0M12 2.5v2.75M10 2.5h4");
}

:global(.njl_u6bdv) {
  d: path("m12.392 10.816l1.567.928a1.75 1.75 0 0 1 0 3.012l-1.567.928a1.75 1.75 0 0 1-2.642-1.505v-1.858a1.75 1.75 0 0 1 2.642-1.505");
}

</style>
