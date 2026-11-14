<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8rchkbuh"/><path class="nh4_ot8ve"/><path class="zvlywgbxr"/><path class="lxaxfex0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-align-right-linear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxaxfex0h) {
  d: path("M10 18H19");
}

:global(.nh4_ot8ve) {
  d: path("M10 10H19");
}

:global(.y8rchkbuh) {
  d: path("M5 6H19");
}

:global(.zvlywgbxr) {
  d: path("M5 14H19");
}

</style>
