<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfsve_32m"/><path class="q04h27byz"/><path class="r49h5hxcs"/><path class="qy4y3cbmh"/><path class="dvgqqgmhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:travel-money-outline-thin" {...props}></Icon>
<style>
:global(.dvgqqgmhk) {
  d: path("M12 11.5v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mfsve_32m) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.q04h27byz) {
  d: path("M5.5 11.5v4");
}

:global(.qy4y3cbmh) {
  d: path("M9 13.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.r49h5hxcs) {
  d: path("M18.5 11.5v4");
}

</style>
