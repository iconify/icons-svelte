<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dpq87fbxj"/><rect class="qz9-9oqaf"/><path class="pj1ivcbsa"/><rect class="ni-uyeb5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stupa" {...props}></Icon>
<style>
:global(.dpq87fbxj) {
  d: path("M12 9.25v-6.5m-1.75 1.5h3.5M10 6.75h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ni-uyeb5a) {
  width: 17.5px;
  height: 3px;
  x: 3.25px;
  y: 18.25px;
  rx: 1px;
}

:global(.pj1ivcbsa) {
  d: path("M5 18.25a7 6.5 0 0 1 14 0Z");
}

:global(.qz9-9oqaf) {
  width: 4px;
  height: 2.5px;
  x: 10px;
  y: 9.25px;
  rx: 0.5px;
}

</style>
