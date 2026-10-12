<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="drbi0rnnl"/><path class="z5i8e4b9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skip-back-10-sharp" {...props}></Icon>
<style>
:global(.drbi0rnnl) {
  d: path("M3.75 12a8.25 8.25 0 1 0 2.42-5.83L3.75 8.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z5i8e4b9v) {
  d: path("M3.75 3.75v4.5h4.5m-.75 2l1.5-1v5.5m5.5-5.5H16v5.5h-3v-5.5z");
}

</style>
