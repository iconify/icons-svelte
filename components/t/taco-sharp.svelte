<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mhf2xabxp"/><path class="mia_k-b1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:taco-sharp" {...props}></Icon>
<style>
:global(.mhf2xabxp) {
  d: path("M2.75 18a9.25 9.25 0 0 1 18.5 0v1H2.75z");
}

:global(.mia_k-b1h) {
  d: path("M6.48 18a1.47 1.47 0 0 1 .74-2.76a1.47 1.47 0 0 1 2.02-2.02a1.47 1.47 0 0 1 2.76-.74a1.47 1.47 0 0 1 2.76.74a1.47 1.47 0 0 1 2.02 2.02a1.47 1.47 0 0 1 .74 2.76");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
