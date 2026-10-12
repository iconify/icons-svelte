<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e_vkywbpd"/><path class="tl1qykb_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:screen-cast-sharp" {...props}></Icon>
<style>
:global(.e_vkywbpd) {
  d: path("M6.5 17.25H2.75V3.75h18.5v13.5H17.5");
}

:global(.tl1qykb_z) {
  d: path("m12.54 15.34l2.92 4.57l.54.84H8l.54-.84l2.92-4.57l.54-.84z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
