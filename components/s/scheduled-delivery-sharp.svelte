<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r5ew85bnh"/><path class="dol289bhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scheduled-delivery-sharp" {...props}></Icon>
<style>
:global(.dol289bhs) {
  d: path("M8.5 11.75h7v6.5h-7zm3.5 0v2");
}

:global(.r5ew85bnh) {
  d: path("M2.75 4.25h18.5v17H2.75zm0 4.5h18.5m-13.5-6v3m8.5-3v3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
