<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vv6cu6ttg"/><path class="v9atpfbxg"/><path class="bj64t1bow"/><path class="afxv9_b8a"/><path class="oq5d88tuy"/><path class="x199_yb0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-duotone-thin" {...props}></Icon>
<style>
:global(.afxv9_b8a) {
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
}

:global(.bj64t1bow) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oq5d88tuy) {
  d: path("M3 12h15");
}

:global(.v9atpfbxg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vv6cu6ttg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x199_yb0z) {
  d: path("M3 17h11a3 3 0 1 1 -3 3");
}

</style>
