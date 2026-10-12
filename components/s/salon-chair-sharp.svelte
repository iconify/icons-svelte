<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ds5lkub1d"/><path class="gykxdjbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:salon-chair-sharp" {...props}></Icon>
<style>
:global(.ds5lkub1d) {
  d: path("M11.25 6.75a5 4 0 0 1 10 0");
}

:global(.gykxdjbst) {
  d: path("M13.75 6.25h4.5v5.5h-4.5zm-8 5.5h12.5v3H5.75zM7 11V9.25h5.5m-.5 5.5v4.5m-5 1h10");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
