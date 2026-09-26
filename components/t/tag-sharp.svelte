<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oy_qfibdp"/><path class="s1f4hpnzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oy_qfibdp) {
  d: path("M2 2L12 2L22 12.8284L12.8284 22L2 12L2 2Z");
}

:global(.s1f4hpnzw) {
  fill: currentColor;
  d: path("M9.5 8C9.5 8.8284 8.8284 9.5 8 9.5C7.1716 9.5 6.5 8.8284 6.5 8C6.5 7.1716 7.1716 6.5 8 6.5C8.8284 6.5 9.5 7.1716 9.5 8Z");
  stroke: none;
}

</style>
