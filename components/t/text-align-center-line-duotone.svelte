<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a01hat8wv"/><path class="y8rchkbuh"/><path class="zvlywgbxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-align-center-line-duotone" {...props}></Icon>
<style>
:global(.a01hat8wv) {
  d: path("M7.5 10H16.5M7.5 18H16.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y8rchkbuh) {
  d: path("M5 6H19");
}

:global(.zvlywgbxr) {
  d: path("M5 14H19");
}

</style>
