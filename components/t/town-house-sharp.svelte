<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="svt2cjb9p"/><path class="u4cz93-kl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:town-house-sharp" {...props}></Icon>
<style>
:global(.svt2cjb9p) {
  d: path("M4.75 5.5h14.5M6 5.5h12v15.75H6zm3 3v2.25m6-2.25v2.25M9 13v2.25");
}

:global(.u4cz93-kl) {
  d: path("M12.75 21.25V16.5h2.5v4.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
