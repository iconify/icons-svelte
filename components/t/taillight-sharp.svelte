<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w8m5b0y_s"/><path class="wqv2yddhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:taillight-sharp" {...props}></Icon>
<style>
:global(.w8m5b0y_s) {
  d: path("M5.25 6.5h16v11H8.5l-1.89-1.64l-1.97-1.72l-1.89-1.64v-6z");
}

:global(.wqv2yddhi) {
  d: path("M13 9h5.75v6H13zM9.75 9v6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
