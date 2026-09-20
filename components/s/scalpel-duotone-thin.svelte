<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-xzyqe3f"/><path class="jmolxjtwy"/><path class="j6hwip25h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scalpel-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6hwip25h) {
  d: path("m13 12 2 2");
}

:global(.jmolxjtwy) {
  d: path("m4 20 8 -8 4 -4 3 3 -4 4 -5 5Z");
}

:global(.v-xzyqe3f) {
  fill: currentColor;
  d: path("m4 20 8 -8 4 -4 3 3 -4 4 -5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
