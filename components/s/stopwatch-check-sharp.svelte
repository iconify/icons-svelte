<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fhcsjwttb"/><path class="si7a6shde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stopwatch-check-sharp" {...props}></Icon>
<style>
:global(.fhcsjwttb) {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

:global(.si7a6shde) {
  d: path("M10 2.75h4m-2 0v3M17.5 8l1.75-1.75M12 13.5l2.75-2.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
