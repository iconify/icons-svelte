<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hdcn_s_df"/><path class="tm1rg8bbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transfer-horizontal-line-duotone" {...props}></Icon>
<style>
:global(.hdcn_s_df) {
  d: path("M20 10L4 10L9.5 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tm1rg8bbr) {
  d: path("M4 14L20 14L14.5 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
