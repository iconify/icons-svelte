<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gc1u27bek"/><path class="uxxy73ggi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ziggurat-sharp" {...props}></Icon>
<style>
:global(.gc1u27bek) {
  d: path("M2.75 20.75V17H5v-4.25h2.5V8.5h2.25v-4h4.5v4h2.25v4.25H19V17h2.25v4.25H2.75z");
}

:global(.uxxy73ggi) {
  d: path("M10.25 9.5h3.5v11.75h-3.5zm0 3.5h3.5m-3.5 3.75h3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
