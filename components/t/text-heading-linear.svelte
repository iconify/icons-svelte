<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyobk-bwz"/><path class="btex5sb2a"/><path class="h3s_qfbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-heading-linear" {...props}></Icon>
<style>
:global(.btex5sb2a) {
  d: path("M19 2V22");
}

:global(.h3s_qfbzc) {
  d: path("M5 12H19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zyobk-bwz) {
  d: path("M5 2V22");
}

</style>
