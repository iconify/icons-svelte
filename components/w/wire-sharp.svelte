<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ynf6gdd5u"/><path class="mjy5fbbwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wire-sharp" {...props}></Icon>
<style>
:global(.mjy5fbbwl) {
  d: path("M10.25 9.75h5.5v4.5h-5.5zm7.25.75l3.75-1.75M17.5 12h3.75m-3.75 1.5l3.75 1.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ynf6gdd5u) {
  d: path("M2.75 18.25C7.25 18.25 6 12 10.5 12");
}

</style>
