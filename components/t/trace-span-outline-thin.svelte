<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crv4i00bu"/><path class="gxfvqwb6p"/><path class="mpqxuepwm"/><path class="lc1sr-eqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trace-span-outline-thin" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.gxfvqwb6p) {
  d: path("M7 7a1.5 1.5 0 0 1 1.5 -1.5h10A1.5 1.5 0 0 1 20 7a1.5 1.5 0 0 1 -1.5 1.5h-10A1.5 1.5 0 0 1 7 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lc1sr-eqo) {
  d: path("M7 19a1.5 1.5 0 0 1 1.5 -1.5h4A1.5 1.5 0 0 1 14 19a1.5 1.5 0 0 1 -1.5 1.5h-4A1.5 1.5 0 0 1 7 19");
}

:global(.mpqxuepwm) {
  d: path("M10 13a1.5 1.5 0 0 1 1.5 -1.5h9A1.5 1.5 0 0 1 22 13a1.5 1.5 0 0 1 -1.5 1.5h-9A1.5 1.5 0 0 1 10 13");
}

</style>
