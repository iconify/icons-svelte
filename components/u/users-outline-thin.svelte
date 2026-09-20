<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8-0ejn0y"/><path class="igyz-cc5b"/><path class="d_xtg74gy"/><path class="zhhqt74pq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:users-outline-thin" {...props}></Icon>
<style>
:global(.d_xtg74gy) {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.igyz-cc5b) {
  d: path("M3 20a5 5 0 0 1 10 0");
}

:global(.q8-0ejn0y) {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.zhhqt74pq) {
  d: path("M13 20a4 4 0 0 1 8 0");
}

</style>
