<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olj_e5cpq"/><path class="mk93lqrnh"/><path class="hzm2gxbyj"/><path class="syh4macvb"/><path class="rsgt5c-rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:task-split-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzm2gxbyj) {
  d: path("M17 8v6");
}

:global(.mk93lqrnh) {
  d: path("M7 8v6");
}

:global(.olj_e5cpq) {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-13A2.5 2.5 0 0 1 3 5.5");
}

:global(.rsgt5c-rz) {
  d: path("M13 16.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3a2.5 2.5 0 0 1 -2.5 -2.5");
}

:global(.syh4macvb) {
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8.5 19h-3A2.5 2.5 0 0 1 3 16.5");
}

</style>
