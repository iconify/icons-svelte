<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="s_9dtpvxy"/><path class="zl2kh1bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:travel-cover-outline-thin" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_9dtpvxy) {
  d: path("M8 15.5h8v5H8Z");
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

:global(.zl2kh1bxb) {
  d: path("M10 15.5v-3h4v3");
}

</style>
