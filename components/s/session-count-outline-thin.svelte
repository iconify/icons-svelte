<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myekf3bzc"/><path class="cpvmwnddk"/><path class="rrxso7m3p"/><path class="tpi3f12bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:session-count-outline-thin" {...props}></Icon>
<style>
:global(.cpvmwnddk) {
  d: path("M2 19a5 5 0 0 1 10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.rrxso7m3p) {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.tpi3f12bz) {
  d: path("M12 19a5 5 0 0 1 10 0");
}

</style>
