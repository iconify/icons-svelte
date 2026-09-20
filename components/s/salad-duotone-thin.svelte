<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu8t8bbdh"/><path class="vd20ei7pe"/><path class="ykkw-8b6k"/><path class="ilf17yx9g"/><path class="k187sabpz"/><path class="kpavcn10r"/><path class="n5cv_rbxc"/><path class="o7aygz06s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:salad-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilf17yx9g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.kpavcn10r) {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

:global(.lu8t8bbdh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n5cv_rbxc) {
  d: path("m5 11 4 -4 4 4");
}

:global(.o7aygz06s) {
  d: path("m11 11 4 -4 4 4");
}

:global(.vd20ei7pe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 11a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ykkw-8b6k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
