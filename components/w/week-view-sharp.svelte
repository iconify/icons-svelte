<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qopwkrz_a"/><path class="yi9vr5hvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:week-view-sharp" {...props}></Icon>
<style>
:global(.qopwkrz_a) {
  d: path("M3.25 3.25h17.5v17.5H3.25zm0 5h17.5M9 8.25v4.25m0 2v6.25m6-12.5v4.25m0 2v6.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yi9vr5hvi) {
  d: path("M9 11.5h6v4H9z");
}

</style>
