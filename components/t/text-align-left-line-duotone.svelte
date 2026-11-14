<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="po0uonb9u"/><path class="y8rchkbuh"/><path class="zvlywgbxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-align-left-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.po0uonb9u) {
  d: path("M5 10H14M5 18H14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.y8rchkbuh) {
  d: path("M5 6H19");
}

:global(.zvlywgbxr) {
  d: path("M5 14H19");
}

</style>
