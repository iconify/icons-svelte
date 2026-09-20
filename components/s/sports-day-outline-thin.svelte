<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ir_a00ama"/><path class="h1f6hnbpb"/><path class="xt3sjtb4p"/><path class="pq9ly31-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sports-day-outline-thin" {...props}></Icon>
<style>
:global(.h1f6hnbpb) {
  d: path("M2 21v-8h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ir_a00ama) {
  d: path("M8 21V8h8v13Z");
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xt3sjtb4p) {
  d: path("M16 13h6v8");
}

</style>
