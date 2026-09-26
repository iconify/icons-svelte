<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yhggpq7zf"/><path class="k8te4qbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:unlock-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k8te4qbon) {
  fill: currentColor;
  d: path("M13.5 16C13.5 16.8284 12.8284 17.5 12 17.5C11.1716 17.5 10.5 16.8284 10.5 16C10.5 15.1716 11.1716 14.5 12 14.5C12.8284 14.5 13.5 15.1716 13.5 16Z");
  stroke: none;
}

:global(.yhggpq7zf) {
  d: path("M16.5 10L16.5 6.5C16.5 4.0147 14.4853 2 12 2C9.5147 2 7.5 4.0147 7.5 6.5L7.5 7.5M4 10L4 22L20 22L20 10L4 10Z");
}

</style>
