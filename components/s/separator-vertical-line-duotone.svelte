<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="va1552nwh"/><path class="x1f4lc3zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-vertical-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.va1552nwh) {
  d: path("M9 18L3 12L9 6M15 18L21 12L15 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.x1f4lc3zb) {
  d: path("M12 2L12 22");
}

</style>
