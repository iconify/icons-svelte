<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fhcsjwttb"/><path class="bnwycijld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timer-play-sharp" {...props}></Icon>
<style>
:global(.bnwycijld) {
  d: path("M9.75 2.75h4.5m-2.25 0v3M17.5 8l1.75-1.75m-8.35 4.62l3.95 2.26l.65.37l-.65.37l-3.95 2.26l-.65.37v-6z");
}

:global(.fhcsjwttb) {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
