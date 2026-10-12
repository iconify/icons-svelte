<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="r6uvok62f"/><circle class="hsg5pubci"/><path class="hgj314i_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:smart-ring-sharp" {...props}></Icon>
<style>
:global(.hgj314i_g) {
  d: path("m9 4.5l3-2.99l3 2.99");
}

:global(.hsg5pubci) {
  cx: 12px;
  cy: 14px;
  r: 4.5px;
}

:global(.r6uvok62f) {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
