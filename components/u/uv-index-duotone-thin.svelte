<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gap0lacnb"/><path class="c5v_de02i"/><path class="jfcsmebdz"/><path class="kqcu0mbfo"/><path class="ic_pehd5a"/><path class="c8wm-2bna"/><path class="e7aqn3bvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:uv-index-duotone-thin" {...props}></Icon>
<style>
:global(.c5v_de02i) {
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.c8wm-2bna) {
  d: path("M9 17v4");
}

:global(.e7aqn3bvb) {
  d: path("M15 17v4");
}

:global(.gap0lacnb) {
  fill: currentColor;
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.jfcsmebdz) {
  d: path("m4.5 3.5 3 3");
}

:global(.kqcu0mbfo) {
  d: path("m19.5 3.5 -3 3");
}

</style>
