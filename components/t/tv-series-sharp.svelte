<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fkvi9krra"/><path class="atdektbnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tv-series-sharp" {...props}></Icon>
<style>
:global(.atdektbnf) {
  d: path("M6.75 4.75h14.5v10.5M5.25 13h1.5m3 0h1.5m3 0h1.5");
}

:global(.fkvi9krra) {
  d: path("M2.75 7.75h15.5v10.5H2.75zm4.75 13.5h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
