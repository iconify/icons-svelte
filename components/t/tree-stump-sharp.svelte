<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yhimfg_0y"/><path class="mrklgdc8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tree-stump-sharp" {...props}></Icon>
<style>
:global(.mrklgdc8d) {
  d: path("M5.75 8.5a6.25 2.5 0 0 0 12.5 0M9.5 14v4.5m8.75-5l2.25-.375l.75-1.875");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yhimfg_0y) {
  d: path("M5.75 8.5a6.25 2.5 0 0 1 12.5 0v11.321l2.5 1.429H3.25l2.5-1.429V17.75Z");
}

</style>
