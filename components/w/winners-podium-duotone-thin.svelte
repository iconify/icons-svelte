<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-mi7nbzz"/><path class="j8ri2qizx"/><path class="o243xubfu"/><path class="qqp18hbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:winners-podium-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8ri2qizx) {
  d: path("M8 21V6h8v15Z");
}

:global(.o243xubfu) {
  d: path("M2 21V11h6");
}

:global(.qqp18hbup) {
  d: path("M22 21v-7h-6");
}

:global(.x-mi7nbzz) {
  fill: currentColor;
  d: path("M8 21V6h8v15Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
