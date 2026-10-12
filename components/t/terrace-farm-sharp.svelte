<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w3m1r4hic"/><path class="gvu5eetdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:terrace-farm-sharp" {...props}></Icon>
<style>
:global(.gvu5eetdc) {
  d: path("M11 21.25V17.5h3.5V14H18v-3.5h3.25");
}

:global(.w3m1r4hic) {
  d: path("M3.53 20.72L20.72 3.53l.53-.53v18.25H3z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
