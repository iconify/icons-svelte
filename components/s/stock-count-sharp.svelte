<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sx_wyqbjl"/><path class="wdv75-boe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stock-count-sharp" {...props}></Icon>
<style>
:global(.sx_wyqbjl) {
  d: path("M9 4.5H5.75v16.75h12.5V4.5H15");
}

:global(.wdv75-boe) {
  d: path("M9 2.75h6v3.5H9zM9 10h6m-6 3.5h6M9 17h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
