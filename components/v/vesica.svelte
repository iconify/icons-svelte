<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wayxywj4x"/><path class="ew_kbi8qu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:vesica" {...props}></Icon>
<style>
:global(.ew_kbi8qu) {
  d: path("M12 6.8a6 6 0 0 1 0 10.4a6 6 0 0 1 0-10.4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wayxywj4x) {
  d: path("M9 6a6 6 0 1 1 0 12A6 6 0 1 1 9 6m6 0a6 6 0 1 1 0 12a6 6 0 1 1 0-12");
}

</style>
